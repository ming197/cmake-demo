# version configuration
cmake_minimum_required (VERSION 2.8)

# project info
project (Demo2)

# add all files under the source directory
# aux_source_directory(<dir> <variable>)
aux_source_directory(. SOURCE_FILES_)

# generate executable files
add_executable(Demo2 ${SOURCE_FILES_})

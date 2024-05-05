# required version
cmake_minimum_required (VERSION 2.8)

# project info
project (Demo3)

# add source files
aux_source_directory(. DIR_SRCS)

# add sub_directory
# the cmake_list.txt and source files under this will be processed
add_subdirectory(math)

# generate the object
add_executable(Demo3 ${DIR_SRCS})

# add the linked library
target_link_libraries(Demo3 MathFunctions)
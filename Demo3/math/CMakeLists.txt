# add source files
aux_source_directory(. DIR_LIB_SRCS)

# generate static linked library
add_library (MathFunctions ${DIR_LIB_SRCS})

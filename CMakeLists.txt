enable_language(C)

file(GLOB_RECURSE GLAD_SRCS include/*.h src/*.c)
add_library(glad STATIC ${GLAD_SRCS})

include_directories(glad
        include
    )

cmake_minimum_required(VERSION 3.16)

set(srcs 
		"main.c"
    )


idf_build_component(SRCS ${srcs}
                    INCLUDE_DIRS "."
                    )


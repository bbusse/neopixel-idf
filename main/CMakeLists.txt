cmake_minimum_required(VERSION 3.16)

set(srcs 
		"main.c"
    )


idf_component_register(SRCS ${srcs}
                    INCLUDE_DIRS "."
                    )


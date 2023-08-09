#
# microtar C library
#

set (SOURCES
		src/microtar.c
	)

add_library(microtar ${SOURCES})
target_compile_features(microtar PUBLIC c_std_11)
target_include_directories(microtar PUBLIC src)

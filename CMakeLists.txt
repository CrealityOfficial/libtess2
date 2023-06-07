
file(GLOB_RECURSE SRCS
  Source/*.h
  Source/*.hpp
  Source/*.cpp
)

file(GLOB_RECURSE INCS
  Include/*.h
  Include/*.hpp
)

			)
__add_real_target(libtess2 lib SOURCE ${SRCS}
								  INC ${INCS}

								  
								)
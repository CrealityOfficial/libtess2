
set(SRCS   Source/bucketalloc.c
					Source/bucketalloc.h
					Source/dict.c
					Source/dict.h
					Source/geom.c
					Source/geom.h
					Source/mesh.c
					Source/mesh.h
					Source/priorityq.c
					Source/priorityq.h
					Source/sweep.c
					Source/sweep.h
					Source/tess.c
					Source/tess.h

)

set( INCS  Include/tesselator.h
    
)

			
__add_real_target(libtess2 lib SOURCE ${SRCS}
								  INC ${INCS}

								  
								)
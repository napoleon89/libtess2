add_library(libtess2 STATIC
        Source/bucketalloc.h
        Source/bucketalloc.c
        Source/dict.h
        Source/dict.c
        Source/geom.h
        Source/geom.c
        Source/mesh.h
        Source/mesh.c
        Source/priorityq.h
        Source/priorityq.c
        Source/sweep.h
        Source/sweep.c
        Source/tess.h
        Source/tess.c
        )
target_include_directories(libtess2 PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/Include)
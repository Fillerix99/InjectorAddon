if(UNIX)
    set(BUILD_HOTPATCHER_SHARED OFF CACHE INTERNAL "")
    set(BUILD_TESTS OFF CACHE INTERNAL "")

    add_subdirectory(hotpatch)
endif()

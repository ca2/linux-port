cmake_minimum_required(VERSION 3.16)
project(port)


if(INCLUDE_AUDIO)

    add_subdirectory(base/id3lib)

endif()


if(NOT ${HAS_SYSTEM_UNAC})

    add_subdirectory(base/unac)

endif()

include_directories(SYSTEM ${GRASS_INCLUDE_DIR})
include_directories(${CMAKE_CURRENT_BINARY_DIR})
ADD_QGIS_GRASS_TESTS(6)

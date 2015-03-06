cmake_minimum_required(VERSION 2.8)

set( MODULE_TARGET_DIR "cmake-${CMAKE_MAJOR_VERSION}.${CMAKE_MINOR_VERSION}" )

install(FILES modules/FindGem.cmake DESTINATION share/${MODULE_TARGET_DIR}/Modules)



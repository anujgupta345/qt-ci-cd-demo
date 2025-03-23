cmake_minimum_required(VERSION 3.10)
project(QtCiCdDemo)

set(CMAKE_CXX_STANDARD 17)
find_package(Qt5 COMPONENTS Core REQUIRED)

add_executable(qt_ci_cd_demo main.cpp)
target_link_libraries(qt_ci_cd_demo Qt5::Core)


cmake_minimum_required(VERSION 2.8)
project(QRCode)
find_package(OpenCV REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})
add_executable(QRCode main.cpp)
target_link_libraries(QRCode ${OpenCV_LIBS})

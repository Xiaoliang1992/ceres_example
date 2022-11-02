cmake_minimum_required(VERSION 2.8)
project(ceres)

find_package(Ceres REQUIRED)
find_package(OpenCV REQUIRED)
include_directories(${CERES_INCLUDE_DIRS})

add_executable(ceres_test ceres_test.cpp)
target_link_libraries(ceres_test ${CERES_LIBRARIES})

add_executable(ceres_test2 ceres_test2.cpp)
target_link_libraries(ceres_test2 ${CERES_LIBRARIES} ${OpenCV_LIBS})
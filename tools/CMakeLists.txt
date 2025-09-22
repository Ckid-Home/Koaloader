cmake_minimum_required(VERSION 3.24)

project(koaloader-tools LANGUAGES CXX)

add_executable(list_common_exports src/list_common_exports.cpp)
target_link_libraries(list_common_exports PRIVATE KoalaBox)

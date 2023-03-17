# main
cmake_minimum_required(VERSION 3.20.0)
project(avm VERSION 0.1.0)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_C_STANDARD 17)

add_compile_definitions(_LOG)

include_directories(
    ./shared/
    ./client/
    ./server/
)

add_subdirectory(./client)
add_subdirectory(./server)

message("Directory: " ./clent ./server)

# server

project(Server VERSION 0.1.0)

# Перебор исходных файлов и их компиляция
file(GLOB_RECURSE SOURCES CONFIGURE_DEPENDS *.cpp)
add_executable(Server ${SOURCES} server.cpp)

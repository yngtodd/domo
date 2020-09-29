cmake_minimum_required(VERSION 3.17)

project(Domo 
    VERSION 0.1.0
    LANGUAGES C
    DESCRIPTION "A Hello world program"
)

add_executable(
    Domo
    src/main.c
    src/hello.c
)

target_link_libraries(
    Domo PUBLIC
)

target_include_directories(
    Domo PRIVATE
    include
)

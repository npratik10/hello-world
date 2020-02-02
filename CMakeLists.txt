#######################################################
#
#              Cmakelist test
#######################################################
cmake_minimum_required(VERSION 3.4)

project(test_project)

include_directories( .
)

list(APPEND hello_src
    "hello.cpp"
)
add_executable(MyExec ${hello_src})
#add_library(helloSrc STATIC ${hello_src})

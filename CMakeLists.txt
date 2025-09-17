cmake_minimum_required(VERSION 4.0)
project(zmq_identity_check)

set(CMAKE_CXX_STANDARD 20)

add_executable(zmq_identity_check main.cpp
        zhelpers.h)

target_link_libraries(zmq_identity_check zmq)

cmake_minimum_required(VERSION 3.30)
project(Server_Client_Socket_Example)

set(CMAKE_CXX_STANDARD 20)

add_executable(client client.cpp)
add_executable(server server.cpp)

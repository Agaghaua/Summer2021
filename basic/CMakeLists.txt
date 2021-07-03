cmake_minimum_required(VERSION 3.19)
project(Network)

set(CMAKE_CXX_STANDARD 17)

add_executable(Network main.cpp hello/hello_server.c hello/hello_client.c echo/echo_server.c echo/echo_client.c handshaking/echo_server_threeway.c handshaking/echo_client_threeway.c handshaking/echo_server2.c handshaking/echo_client2.c)
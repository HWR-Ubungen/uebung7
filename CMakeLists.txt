cmake_minimum_required(VERSION 3.27)
project(uebung7 C)

set(CMAKE_C_STANDARD 11)

add_executable(A1 aufgabe1.c palindromLIB/palindrom.c)
add_executable(A2 aufgabe2.c modules/list.c)
add_executable(A3 aufgabe3.c modules/geometrics.c)
add_executable(A4 aufgabe4.c)
add_executable(A5 aufgabe5.c)

target_link_libraries(A1 m)
target_link_libraries(A2 m)
target_link_libraries(A3 m)
target_link_libraries(A4 m)
target_link_libraries(A5 m)
cmake_minimum_required(VERSION 3.27)
project(aflnet_replay C)

set(CMAKE_C_STANDARD 11)

add_executable(afl-replay afl-replay.c aflnet.c)
add_executable(aflnet-replay aflnet-replay.c aflnet.c)


cmake_minimum_required(VERSION 2.8.12)

project(linux_list C)

set(EMPTY
src/empty.c)

add_executable(linux_list ${EMPTY})
target_include_directories(linux_list PUBLIC include)

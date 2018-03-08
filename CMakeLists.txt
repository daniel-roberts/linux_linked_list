cmake_minimum_required(VERSION 2.8.12)

project(linux_list C)

set(EMPTY
src/empty.c)

add_library(linux_list ${EMPTY})
target_include_directories(linux_list PUBLIC
                           ${PROJECT_SOURCE_DIR}/include)


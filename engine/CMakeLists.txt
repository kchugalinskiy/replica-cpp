cmake_minimum_required(VERSION 3.0) 

project(replicacpp CXX)

file(GLOB SOURCES *.cpp)

include_directories(../include)

add_library(replicacpp STATIC ${SOURCES})
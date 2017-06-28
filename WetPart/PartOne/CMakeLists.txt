cmake_minimum_required(VERSION 3.7)
project(PartOne)

set(CMAKE_CXX_STANDARD 11)



set(SOURCE_FILES Enigma.h EscapeRoom.c EscapeRoom.h Exceptions.h EscapeRoomWrapper.cpp EscapeRoomWrapper.h)
add_executable(PartOne ${SOURCE_FILES})
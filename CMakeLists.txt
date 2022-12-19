cmake_minimum_required(VERSION 3.24)
project(vending)

set(CMAKE_CXX_STANDARD 20)

add_executable(vending main.cpp Snack.h Snack.cpp SnackSlot.h SnackSlot.cpp VendingMachine.h VendingMachine.cpp)

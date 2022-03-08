cmake_minimum_required(VERSION 3.15)
project(BESLE_PlusPlus)

set(CMAKE_CXX_STANDARD 14)

add_executable(User Drivers/Users/JuanAlvarez/main.cpp)
add_executable(Elasticity Drivers/Elasticity/steady_motion.cpp)
cmake_minimum_required(VERSION 3.22)

project(AgeOfWar)

add_subdirectory(libs/BlockyEngine/engine)

add_executable(${PROJECT_NAME} main.cpp)

target_link_libraries(${PROJECT_NAME} Blocky::Engine)
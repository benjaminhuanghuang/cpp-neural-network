cmake_minimum_required(VERSION 3.14)

project(demo.exe VERSION 1.0.0 LANGUAGES CXX)


set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)



#=================== INCLUSION OF Project Files ================#
add_executable(${CMAKE_PROJECT_NAME}
  mian.cpp
  MLP.cpp
)

#===================== LINKING LIBRARIES =======================#
target_link_libraries(${CMAKE_PROJECT_NAME})
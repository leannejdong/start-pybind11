cmake_minimum_required(VERSION 3.1)
project(start-pybind11)

set(MY_PYBIND ${MY_CURR}/extern/pybind11)

#add_subdirectory(${MY_PYBIND})
add_subdirectory(extern/pybind11)
pybind11_add_module(example_pb example_pb.cpp)
#target_link_module(example_pb PUBLIC example)

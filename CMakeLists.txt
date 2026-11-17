cmake_minimum_required(VERSION 3.31)
project(Raytrace)

set(CMAKE_CXX_STANDARD 20)

add_executable(Raytrace main.cpp vec.h ray.h camera.h object.h Material.h
        AABB.h
        BVH.h
        Texture.h)

cmake_minimum_required(VERSION 3.25)

set(XDP_VERSION "1.0.0" CACHE STRING "wm version")
project(xdp-root VERSION ${XDP_VERSION})

add_subdirectory(xdp-pass)
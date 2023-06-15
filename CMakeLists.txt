cmake_minimum_required(VERSION 3.12)

option(WML_USE_SDL "use SDL" ON)
option(WML_BUILD_EXAMPLE "use SDL" OFF)

project(wml)

if(WML_USE_SDL)
	add_subdirectory(third_party/SDL)
endif()
cmake_minimum_required(VERSION 3.15)
project(sweeper)

set(CMAKE_CXX_STANDARD 17)


cmake_minimum_required(VERSION 3.15)
project(sweeper)

set(CMAKE_CXX_STANDARD 17)

# SDL2 last 

add_executable(sweeper
sweeper.cpp
# "app_icon.rc"
)
set(CMAKE_WINDOWS_EXPORT_ALL_SYMBOLS ON)
set_target_properties(sweeper PROPERTIES
LINK_FLAGS "/SUBSYSTEM:CONSOLE"
WIN32_EXECUTABLE TRUE
)
#/*
#-----------------------------------------------------------------------------
#Filename:    CMakeLists.txt
#-----------------------------------------------------------------------------
#
#This source file is part of the
#   ___                 __    __ _ _    _ 
#  /___\__ _ _ __ ___  / / /\ \ (_) | _(_)
# //  // _` | '__/ _ \ \ \/  \/ / | |/ / |
#/ \_// (_| | | |  __/  \  /\  /| |   <| |
#\___/ \__, |_|  \___|   \/  \/ |_|_|\_\_|
#      |___/                              
#      Tutorial Framework
#      http://www.ogre3d.org/tikiwiki/
#-----------------------------------------------------------------------------
#*/
cmake_minimum_required(VERSION 2.6)

set(APP "OgreApp")
 
set(HDRS
	./src/OgreApplication.h
    ./src/GameState.h
    ./src/InputEventListener.h
    ./src/InputSystemManager.h
    ./src/GuiManager.h
    ./src/TerrainManager.h
    ./src/RobotsCreator.h
    ./src/BasicCameraManager.h
)
 
set(SRCS
	./src/OgreApplication.cpp
    ./src/GameState.cpp
    ./src/InputSystemManager.cpp
    ./src/GuiManager.cpp
    ./src/TerrainManager.cpp
    ./src/RobotsCreator.cpp
    ./src/BasicCameraManager.cpp
)
 
include("tools/cmake/common.cmake") 

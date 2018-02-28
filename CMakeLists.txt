cmake_minimum_required(VERSION 3.9)
project(ProjetTram)

set(CMAKE_CXX_STANDARD 11)

add_executable(ProjetTram Sources/main.cpp Sources/Tram.cpp Headers/Tram.h Sources/Arret.cpp Headers/Arret.h Sources/Ligne.cpp Headers/Ligne.h
        Sources/Liste.cpp Headers/Liste.h Sources/File.cpp Headers/File.h Sources/Position.cpp Headers/Position.h Sources/winbgi.cpp Headers/graphics.h)
cmake_minimum_required(VERSION 3.18.4)

project(nuweb LANGUAGES C VERSION 1.60)

add_executable(nuweb arena.c global.c html.c input.c latex.c main.c names.c output.c pass1.c scraps.c)
install(TARGETS nuweb)

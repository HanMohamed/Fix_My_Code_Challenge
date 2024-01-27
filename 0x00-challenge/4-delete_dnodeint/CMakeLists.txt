cmake_minimum_required(VERSION 3.24)
project(4_delete_dnodeint C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(4_delete_dnodeint
        add_dnodeint_end.c
        delete_dnodeint_at_index.c
        free_dlistint.c
        lists.h
        main.c
        print_dlistint.c)

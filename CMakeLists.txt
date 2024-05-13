cmake_minimum_required( VERSION 3.22.1 )

project( Assegnamento
        VERSION 0.1
        DESCRIPTION "Assegnamento gdb valgrind cmake" )

add_compile_options( -Wall -pedantic -Wextra -Werror )

add_subdirectory( gdb )

add_subdirectory( valgrind )

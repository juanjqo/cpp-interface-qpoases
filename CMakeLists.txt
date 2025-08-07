CMAKE_MINIMUM_REQUIRED(VERSION 3.22...3.26)
PROJECT(dqrobotics-interface-qpoases)
set (CMAKE_CXX_STANDARD 17)

################################################################
# INSTALL HEADERS
################################################################

INSTALL(FILES
    include/dqrobotics/solvers/DQ_QPOASESSolver.h
    DESTINATION "include/dqrobotics/solvers")

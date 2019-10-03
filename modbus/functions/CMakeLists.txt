add_library(functions mbfunccoils.c mbfuncdiag.c mbfuncdisc.c mbfuncholding.c mbfuncinput.c mbfuncother.c mbutils.c)
target_include_directories(functions PRIVATE ../include)
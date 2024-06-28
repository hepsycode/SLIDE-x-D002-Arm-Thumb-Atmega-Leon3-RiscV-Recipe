# SLIDE-x-D002-Arm-Thumb-Atmega-Leon3-RiscV-Recipe
This repository contains the results of executing the SLIDE-x framework with the ISS tools for the Arm, Thumb, Atmega328/P, Leon3, RiscV, and the Recipe benchmark.

The folder contains SLIDE-x-RES results (i.e., code profiling, code characteristics, SW size, and timing metrics) extracted using the SLIDE-x framework available at the following link: https://github.com/hepsycode/SLIDE-x.

1. **SLIDE-x-RES**: Result datasets generated during the Profiling/Simulation activities;
    - RECIPE_DECIMAL: Recipe benchmark results with datatypes Float and Double for the following functions: bs, bsort100, cnt, fdct, fibcall, insertionsort, lud, matrix_mult, select, shell_sort;
    - RECIPE_INT: Recipe benchmark results with datatypes int8. int16, int32, int64 for the following functions: bs, bsort100, cnt, fac, fdct, fft, fibcall, insertionsort, lud, matrix_mult, park_miller, prime, select, shell_sort, sqrt;

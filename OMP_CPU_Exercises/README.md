# OpenMP Exercises 

This directory contains exercises and solutions for a hands-on
OpenMP course.  Information about these programs can be found
in the comments and in the slides from the course.

Most of these programs can be directly compiled and run. For
example, for the basic pi program:

     >  gcc -fopenmp pi.c
     >  ./a.out

Note that even the sequential programs need OpenMP since we use
the omp_get_wtime() timing function. 

You can also work with the makefile by changing definitions near
the beginning of the file to point to the right compiler. You can
then test all the code with makefile build target:

    > make test

Solutions to all the exercises can  be found in the Solutions 
directory.  The directory Challenge_Problems contains additional 
exercises for more advanced students.  These have not been as carefully 
tested and may have problems building and running on some systems.

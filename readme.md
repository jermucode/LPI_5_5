This is exercise 5.5 from Kerrisk's "The Linux Programming Interface"
The task is to write a program that checks that duplicated file descriptors
share a file offset value and open file status flags.

This is just a main function to check it, one can always extend this
to be a separate function where you can pass file descriptors to be checked, 
but the logic seems to work

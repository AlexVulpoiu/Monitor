# Monitor
Implementation of a Monitor Object in C using a conditional variable to synchronize the treads and a mutex. The monitor is used to solve the bounded buffer producer-consumer problem.

# Compiled with:
$ gcc Monitor.h Monitor.c main.c -o main -pthread

# Run with:
$ ./main

# Input:
buffer_size

number_of_producers

producers_values

number_of_consumers

consumers_values

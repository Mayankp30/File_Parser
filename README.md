# File_Parser

Part 1

This program is currently a single threaded process.
Objective is to make this a multi-threaded program such that the reading of files is done concurrently.
To do this, we ll need to use the pthreads library.
Be careful to ensure that all threads have completed running before exiting and that you have destroyed any objects you created.


Part 2

The current fileparse.c loops through logs and displays the line and the size of the line. 
The objective of the second part of this exercise is to get a count of the unique number of IP addresses in the log file.
Note: the IP address is the first set of numbers on each line and it indicates the IP of the person that visited that page.


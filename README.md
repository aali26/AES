# AES Optimization Project 

## How to Perform gprof 
The following steps have been tested on Linux and and gcc 
* compile your code using the command gcc -Wall -pg src_code.c -o output_name 
* Run the output file 
* On terminal, type the command gprof output_name gmon.out > analysis_output.txt 

## How to perform Valgrind analysis 
make sure that you have a valgrind installed on your system or install it using the command sudo apt-get install valgrind. once it is installed you may perform the type the following command on your terminal 
valgrind --leak-check=full --show-leak=all --track-origins=yes --verbose --log-file=valgrind.txt ./executable_file 


#### How to work with github 
https://youtu.be/EL2It1cQP4c

# Linux-System-Call
Linux System Call to prints details of the given process using its PID along with a test c program.

## Usage
1. To patch the diff file to a linux kernel, then enter the kernel directory and run the command:
    `patch -p1 -R < diff.txt`
2. Compile and install the kernel.
3. To run the system call sh_task_info in a c program, use the system call number 440.
4. To read the details written, write `dmesg | tail` in linux terminal.
5. To compile and run the test.c program, run `gcc -o test test.c` and `./test "PID" "filename"`. The PID of the process and the name of the file to save the process details.


## Assignment Details
Course Project for Operating Systems (CSE231)
Instructor : Dr. Arani Bhattacharya

This assignment is based on writing a system call in linux kernel 5.9.1 named sh_task_info that writes the process name, its PID, the state of process, priority, nice value and vruntime value and also saves the details in the file named. 
This system call can be called through a c program, as given in the test.c file.


Skills Used : C Programming Language, Linux

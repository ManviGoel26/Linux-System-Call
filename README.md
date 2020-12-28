# Linux-System-Call
Linux System Call to print details of the given process using its PID along with a tese c program.

## Usage
1. To patch the diff file to a linux kernel, then enter the kernel directory and run the command:
    `patch -p1 -R < diff.txt`
2. Compile and install the kernel.
3. To run the system call sh_task_info in a c program, use the system call number 440.
4. To read the details written, write dmesg | tail.


## Assignment Details
Course Project for Operating Systems (CSE231)
Instructor : Dr. Arani Bhattacharya

This assignment is based on writing a system call in linux kernel 5.9.1 named sh_task_info that writes the process name, its PID, the state of process, priority, nice vale and vruntime value. 
This system call can be called through a c program, as given in the test.c file.


Skills Used : C Programming Language, Linux

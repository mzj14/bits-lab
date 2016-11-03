# bits-lab
First coding home work for Computer Architecture

Note:

1. When running "make" command in the project directory on Ubuntu 16.04 (you can run "lsb_release -a" to find your Ubuntu version), 
   an error may occured: "Can not find file or directory <sys/cdefs.h>". 
   
   In such case, please run "sudo apt-get install gcc-multilib" to install the necessary files.
   
2. When doing bit shift, e.g. a << n, gcc won't shift bit if (n >= 32), thus a == a << n
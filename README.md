# xv6-Fall-2021
## Introduction
### What is xv6?
Xv6 is a teaching operating system developed in the summer of 2006 for MIT's operating systems course. 
For many years, MIT had no operating systems course. In the fall of 2002, one was created to teach operating systems engineering. In the course lectures, the class worked through Sixth Edition Unix (aka V6) using John Lions's famous commentary. In the lab assignments, students wrote most of an exokernel operating system, eventually named Jos, for the Intel x86. Exposing students to multiple systems–V6 and Jos–helped develop a sense of the spectrum of operating system designs.
V6 presented pedagogic challenges from the start. Students doubted the relevance of an obsolete 30-year-old operating system written in an obsolete programming language (pre-K&R C) running on obsolete hardware (the PDP-11). Students also struggled to learn the low-level details of two different architectures (the PDP-11 and the Intel x86) at the same time. By the summer of 2006, MIT had decided to replace V6 with a new operating system, xv6, modeled on V6 but written in ANSI C and running on multiprocessor Intel x86 machines. Xv6's use of the x86 makes it more relevant to students' experience than V6 was and unifies the course around a single architecture. Adding multiprocessor support requires handling concurrency head on with locks and threads (instead of using special-case solutions for uniprocessors such as enabling / disabling interrupts) and helps relevance. Finally, writing a new system allowed MIT to write cleaner versions of the rougher parts of V6, like the scheduler and file system. 6.828 substituted xv6 for V6 in the fall of 2006.
### Why xv6? 
Xv6 operating system is used as a programming project in most of the well-known universities such as MIT, Columbia, etc… . 
But the main reason we chose xv6 is that we want students to engage with kernel programming and we want them to learn how to develop an operating system so that if you start working in a team, developing operating system you would probably know the ups and downs. Another reason for choosing xv6 is that, what is thought throughout the course can be used to make some crucial modifications in this operating system and that is what we want you to do.
### But what do we expect you to do?
throughout the course according to what you have learnt we expect you to make some modifications so that you will get to know the  xv6 operating system better and you will see that developing an operating system is not as hard as you imagined and it is just a piece of cake.
### How are you going to make theses modifications?
Well your xv6 project is divided into two phases.
In the first two phases we want you to make some modifications to get to know with xv6 operating system and during that I will be available to help you throughout the course so don’t worry.
In the second phase what you are going to do, is to make some modifications to xv6 just like what you have done in the first two phase but it is going to be a little bit of challenge.
### How are you going to do it?
The very first thing we want you to do is to create teams of two members and create a private GitHub repository so that we can see you making progress(you could either add me or the instructor to your git repository).
You could also use gitlab or other repository managers but we prefer GitHub.
### xv6 Sources :
#### The latest xv6 source is available via : 
git clone git://pdos.csail.mit.edu/xv6/xv6.git
## Xv6 kernel hacking 
### These three phases all are to be done inside the xv6 kernel based on an early version of Unix and developed at MIT. 
#### Phase 1 (intro) 
This first phase is just a warmup and is for you to engage with xv6.
In the first phase and in your very first experience with xv6 you are expected to add two system calls to xv6.
First you need to setup a virtual machine and install a fresh ubuntu operating system on it and then you need to install qemu virtual machine so that you will be able to run xv6 on qemu.

- `int getreadcount(void)`    
Returns the value of a counter which is incremented every time any process calls the read() system call.   
You have to define a variable for the values of read counter. (e.g. readcount)  

- `int getprocs(void)`    
returns the number of processes that exist in the system at the time of the call.
#### Phase 2
In this part you are going to make some crucial modifications. <br />
#### Phase 3 (main)
In this part you are going to make some crucial modifications. <br />
#### Staff
Instructor: [Dr.Seyyed Ahmad Javadi](https://github.com/sajavadi) <br />
Course Assistant: [Mahan Ahmadvand](https://github.com/2000mahan) <br />
Course Assistant: [Arman Hatami](https://github.com/armanhtm) <br />
Course Assistant: [Mahdi Rezaie](https://github.com/mahdirezaie336) <br />
Course Assistant: [Mahdi Rahmani](https://github.com/Mahdi-Rahmani) <br />
Course Assistant: [Mohammad Reza Qaderi](https://github.com/MohammadRezaQaderi) <br />

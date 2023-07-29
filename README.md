



# SIMPLE SHELL PROJECT

![Neutral Creative Professional LinkedIn Article Cover Image](https://github.com/Mardie328/simple_shell/assets/92341910/c90e9c7e-fd1a-4fb1-88e5-2f0db3a4ef31)


## Table of Contents 📑
* [Description](#description)
* [Features](#features)
* [Getting Started](#getting-started)
* [Usage](#usage)
* [Commands](#commands)
* [Authors](#authors)

## Description ✨
The Simple Shell Project is an _ALX Software Engineering Program_ project that involves building a customized simple [shell](https://en.wikipedia.org/wiki/Shell_(computing)). It was built using C programming language. The shell prompts users to input commands, parses these commands, delivers it to the system for execution, and shows the corresponding output in your command terminal.  

This project was compiled on `Ubuntu 20.04 LTS` using `gcc`, using the options `-Wall -Werror -Wextra -pedantic -std=gnu89`.

## Features 📚


## Getting Started 🚀

1. Clone [this repository](https://github.com/Mardie328/simple_shell) using:  
    for HTTPS,  
    ```
    git clone https://github.com/Mardie328/simple_shell.git
    ```  
    for SSH,  
    ```
    git clone git@github.com:Mardie328/simple_shell.git
    ```
2. Change your directory into the simple shell program using:  
    ```
    cd simple_shell
    ```
  
3. Compile using:  
    ```
    gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
    ```  
  
4. Start the shell using:  
    ```
    ./hsh
    ```

    
   **To exit the shell, use `ctrl + D`, `exit()` command, or the word `exit`.**

  

## Usage 🛠️
Your shell should work like this in an interactive mode:
```
$ ./hsh
($) /bin/ls
hsh main.c shell.c
($)
($) exit
$
```

And also in non-interactive mode:
```
$ echo "/bin/ls" | ./hsh
hsh main.c shell.c test_ls_2
$
$ cat test_ls_2
/bin/ls
/bin/ls
$
$ cat test_ls_2 | ./hsh
hsh main.c shell.c test_ls_2
hsh main.c shell.c test_ls_2
$
```

## Commands 📋

## Authors 👥
* **Taofeek Mardiyyah A.**
   * [Email](taofeekmardiyyah@gmail.com)
   * [Twitter](https://twitter.com/TechieHijabie)
   * [LinkedIn](https://linkedin.com/in/mardiyyah-taofeek)
   
* **Holy Ovwiurhobo**
   * [Email]()
   * [Twitter]()
   * [LinkedIn]()


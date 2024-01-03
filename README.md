# Bash-Scripting
Here goes the stuff I'm picking up while Learning Bash Scripting

The repo provides an essential bigginer introduction to `Bash commands`, introducing biefely the necessary commands that help navigate through bash and defining the concepts around as it's preparing for complex and advanced bash scripting applications. 


## The Definition: Wrapping The Head Around

`Bash` stands for `Bourne Again SHell` which I find a clever name considering that it combines the name `Bourne` from  `Bourne Shell` while providing a self-description such that is a "Born Again" Shell or an improved application of the original Bourne Shell `sh` developed by Stephen Bourne in the 1970s. 

Over all, `Bash` is an application interface, or a command processor that runs in a text window where the user types commands that cause actions using the system recources, in other words it helps the user accessing the system's hardware recources and capabilities with commands that can be stored in a file to automate actions and these commands are then refered to as the `shell scripts`. `Bash` helps the user to read, write and execute commands from a `shell script` file. And in this repo that is what we are intending to learn how to do: `read`, `write` and `execute` shell scripts as this is considered as a key ability for anyone venturing in the computer programming field, no matter which side of the field particularly, that means frontend, backend, fullstack, data scientist, machine learning engineer, or anything in between, the moment you get into computer programming, you definetely need to wrap your head around `shell scripting` or `bash scripting` in our case as we are assuming the `Bash` application as the application being used.


## The Navigation: A Comprehensive Guide

The Bourne Again Shell :smile, provides a robust set of commands for navigating the file system, creating and manipulating files and directories, and executing operations efficiently from the command line. In this guide, we explore the essential Bash navigation commands, along with concepts like wildcards, directory stacks, and file manipulation.

Consider this is a comprehensive guide that provides an overview - no so overview of essential Bash navigation concepts for effective file and directory management. Becoming familiar with these commands is a sure deal of gaining the needed skills to navigate, manipulate, and automate somne boring tasks, or even the fun ones just because you can - efficiently in the command line :smile.

### **1. Basic Navigation:**

- **`ls` - List Files and Directories:**
  ```bash
  ls
  ```

- **`cd` - Change Directory:**
  ```bash
  cd /path/to/directory
  ```

- **`pwd` - Print Working Directory:**
  ```bash
  pwd
  ```

- **`cp` - Copy Files or Directories:**
  ```bash
  cp source destination
  ```

- **`mv` - Move or Rename Files and Directories:**
  ```bash
  mv source destination
  ```

- **`rm` - Remove/Delete Files or Directories:**
  ```bash
  rm filename
  ```

- **`mkdir` - Create a New Directory:**
  ```bash
  mkdir directory_name
  ```

- **`echo` - Print Text to the Terminal:**
  ```bash
  echo "Hello, World!"
  ```

- **`cat` - Concatenate and Display File Content:**
  ```bash
  cat filename
  ```


### **2. Concepts:**

- **Path:** The location of a file or directory in the file system. Paths can be absolute (from the root directory) or relative (from the current directory).

- **Permissions:** Files and directories have read, write, and execute permissions for the owner, group, and others.

- **Variables:** Bash scripting involves using variables to store and manipulate data.

- **Functions:** Functions allow you to group code into reusable blocks.

- **Conditional Statements:** Use `if`, `else`, and `elif` for conditional execution.

- **Loops:** Bash supports `for` and `while` loops for iterating over sequences.

### **3. Wildcards and Case Sensitivity:**

- **Asterisk `*`:** Matches zero or more characters.
- **Question Mark `?`:** Matches a single character.
- **Square Brackets `[ ]`:** Matches a range or specific characters.
- **Curly Braces `{ }`:** Generates strings based on patterns.

- **Case Sensitivity:**
  ```bash
  *[[:upper:]]*   # Matches any filename containing at least one uppercase letter
  *[[:lower:]]*   # Matches any filename containing at least one lowercase letter
  ```

### **4. Directory Stacks:**

- **`pushd` - Push Directory onto Stack:**
  ```bash
  pushd /path/to/directory
  ```

- **`popd` - Pop Directory from Stack:**
  ```bash
  popd
  ```

### **5. Advanced Commands:**

- **`grep` - Search for Patterns in Files:**
  ```bash
  grep pattern filename
  ```

- **`sed` - Stream Editor for Text Processing:**
  ```bash
  sed 's/old_text/new_text/' filename
  ```

- **`awk` - Powerful Text Processing Tool:**
  ```bash
  awk '{print $1}' filename
  ```

- **I/O Redirection and Pipelines:**
  ```bash
  command1 > output.txt
  command1 | command2
  ```

### **6. Finding and Executing Commands:**

- **`whereis` - Locate Binary, Source, and Manual Files:**
  ```bash
  whereis command_name
  ```

- **`which` - Locate Binary Executable in the PATH:**
  ```bash
  which command_name
  ```

### **7. File Creation and Manipulation:**

- **`touch` - Create Empty Files or Update Timestamps:**
  ```bash
  touch myfile.txt
  ```

- **`mv` - Move or Rename Files and Directories:**
  ```bash
  mv source destination
  ```

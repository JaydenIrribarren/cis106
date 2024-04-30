---
name: Jayden Irribarren
semester: Spring 2024
course: cis 106
---

# Notes 6

## What is Awk?
  What is awk: Awk is a scripting language used for processing and displaying text. It can work with text files or from a standard output. 
  - Usage: awk + options + {awk command} + file + file to save (optional)
  - Examples:
  - awk '{print $1}' ~/Documents/Csv/cars.csv
  - awk -F: '{print $1}' /etc/passwd

## What is Sed?
  SED is a stream editor that perform operations on files and standard output. It can search, find and replace, insert, and deletion. By using SED you can edit any files without opening them
- Usage: sed options + sed script + file
- Examples: 
- sed 's/pizza/rice/4' shopping-list.lst
- sed 's/pizza/rice/' shopping-list.lst

## What is Alias?
Alias is a shorthand for more complicated command. It does not persist unless you save them in your .bashrc or .bash_aliases file.
- Usage: alias name_of_alias="command here"
- Examples: 
- alias update="sudo apt update; sudo upgrade -y; sudo apt full-upgrade -y"
- alias clean="sudo apt autoremove -y; sudo autoclean; sudo apt purge;"

## What is less?
The pipe that allows you to redirect the standard output of a command to the standard input of another.
- Usage: command_1 | command_2 | command_3 | .... | command_N
- Examples: 
- man ls | grep "human-readable"
- man ls | grep "^[[:space]]*[[:punct:]]'


---
name: Jayden Irribarren
semester: Spring 2024
course: cis 106
---

## Notes 5

### Cat
- Cat command is used for displaying the content of a file.
- Usage: cat + option + file(s) to display
  Examples: 
- cat todo.lst
- cat ~/Documents/todo.lst
- cat --help

### Tac
- The tac command is used for displaying the content of a file in reverse order. Similar to cat commands, tac files and displays the output of the concatention
- Usage: tac + option + file(s) to display
  Examples:
- tac todo.md
- tc ~/Documents/todo.md

### Head
- The head command displays the top N number of lines of a given file. By default, it prints the first 10 lines. If more than one file name is provided then data from each file is preceded by its file name.
- Usage: head + option + file(s)
  Examples:
- head ~/Documents/Book/dracula.txt
- head -5 ~/Documents/Book/dracula.txt (to display the first 5 lines of file)

### Tail
- The tail command displays the last N number of lines of a given file. By default, it prints the last 10 lines. If more than one file name is provided then data from each file is preceded by its file name.
- Usage: tail + option + file 
  Examples:
- tail ~/Documents/Book/dracula.txt
- tail -5 ~/Documents/Book/dracula.txt

### Cut
- The cut command is used to extract specific section of each line of a file and display it to the screen.
- Usage: cut + option + file(s)
 Examples:
- cut -d ':' -f1 /etc/passwrd
- cut -d ':' -f1,7 /etc/passwd

### Sort 
- The sort command is used for sorting files. 
- Usage: sort + option + file
  Example:
- sort users.lst
- sort -o sorted.lst users.lst

### WC
- The wc command is used for printing the numbers of lines, characters and bytes in a file.
- Usage: wc + option + file(s)
  Examples:
- wc -m users.txt
- wc -l users.txt

### Diff
- The diff command compares files and displays the differences between them
- Usage: diff + option + file1 + file2
 Example:
- diff cars.csv cars-backup.csv
- diff -y cars.csv cars-backup.csv

### Grep
- Grep is used to search text in given file. Grep works line by line basis (it matches the search criteria in a line by line basis)
- Usage: grep + option + search criteria + file(s)
  Example
- grep 'dracula' ~/Documents/dracula.txt
- grep -i 'dracula' ~/Documents/Books/dracula.txt
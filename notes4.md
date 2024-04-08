---
name: Jayden Irribarren
semester: Spring 2024
course: cis 106
---

## Notes 4

### How to use `*` Wildcard
The way that you use `*` is if you want to list all files with a particular file extension... 
For ex: 
- ls *.txt.

### How to use `?` Wildcard
? is when you can list all of the hidden files.
For example:
- ls .??*

### How to use `[]` Wildcard
`[]` is used to match a single character in a range.
- ls f[aeiou]*

### How to use `{}` Wildcard
- It allows you to generate arbitrary strings to use commands.
- mkdir -p music/{jazz,rock}/{mp3files,videos,oggfiles}/new{1..3}
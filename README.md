# Line &nbsp; ![DEVELOPMENT STATUS: complete](https://badgen.net/badge/DEVELOPMENT%20STATUS/complete/green)

A simple bash script to display a specific line from a file or input

## Usage examples:
```console
$ line 19 data.txt
```
Will display the 19th line of the data.txt file

```console
$ cat file.txt | line 21
```
Will display the 21st line of what ever was piped into it, in this case the content of file.txt

## How-to:
1. Put the **line** script with your other **bin**aries, or in a separate folder, but then don't forget to include that folder to your **PATH** variable (There are plenty of resources out there if you don't know how to do the latter)
2. Add execution rights to it: ```$ chmod u+x line```
3. Rehash to use instantly: ```$ rehash``` 

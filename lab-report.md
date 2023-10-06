# cd Command
``` bash
[user@sahara ~]$ cd
[user@sahara ~]$
```
Working directory: /home

cd command with no argument just change to the root directory, but we already are in the root directory. Thus, nothing changed.
No error.

---
``` bash
[user@sahara ~]$ cd lecture1
[user@sahara ~/lecture1]$
```
Working directory: /home/lecture1

cd command change the current directory to lecture1, so we see lecture1 after ~
No error

---
``` bash
[user@sahara ~]$ cd lecture1/Hello.java
bash: cd: lecture1/Hello.java: Not a directory
[user@sahara ~]$
```
Working directory: /home/lecture1

cd command is used to change the directory to a new directory, so the terminal tells us that the Hello.java is not a directory. Thus, the error happened.

---
# ls Command

``` bash
[user@sahara ~]$ ls
lecture1
[user@sahara ~]$
```
Working directory: /home

ls command with no argument implies that we want to list the root folder. The lecture1 is the folder within /home or root folder, so the ls command displays the lecture1.
No error

---
``` bash
[user@sahara ~]$ ls lecture1
Hello.class  Hello.java  messages  README
[user@sahara ~]$
```
Working directory: /home

All the files and folders within the lecture1 folder are displayed because of the ls command.
No error

---
``` bash
[user@sahara ~]$ ls lecture1/messages/en-us.txt
lecture1/messages/en-us.txt
[user@sahara ~]$
```
Working directory: /home

There are no files and folders within the files themselves, so the ls command just shows the given path.
No error.

---
# cat Command

``` bash
[user@sahara ~]$ cat
^C
[user@sahara ~]$ 
```
Working directory: /home

Nothing happened when the cat command with no argument. And I have to use ^C to get out of the terminal.
The error might happen because the cat command needs a file to print the context.

---
``` bash
[user@sahara ~]$ cat lecture1/messages
cat: lecture1/messages: Is a directory
[user@sahara ~]$ 
```
Working directory: /home

Because "messages" is not a file, the terminal reminds us that "messages" is a directory.
Error happened because messages is not a file.

---
``` bash
[user@sahara ~]$ cat lecture1/messages/th.txt
สวัสดีชาวโลก
[user@sahara ~]$ 
```
Working directory: /home

the cat command prints the contents of the th.txt file.
No error.

---

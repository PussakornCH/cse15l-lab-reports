``` bash

```
# cd Command
``` bash
[user@sahara ~]$ cd
[user@sahara ~]$
```
No directory working. cd command connects the system with its argument, so no argument means no connects. No error.

``` bash
[user@sahara ~]$ cd lecture1
[user@sahara ~/lecture1]$
```
Lecture 1 is working. cd command ... No error

``` bash
[user@sahara ~]$ cd lecture1/Hello.java
bash: cd: lecture1/Hello.java: Not a directory
[user@sahara ~]$
```
Explain

# ls Command

``` bash
[user@sahara ~]$ ls
lecture1
[user@sahara ~]$
```
``` bash
[user@sahara ~]$ ls lecture1
Hello.class  Hello.java  messages  README
[user@sahara ~]$
```


``` bash
[user@sahara ~]$ ls lecture1/messages/en-us.txt
lecture1/messages/en-us.txt
[user@sahara ~]$
```

# cat Command

``` bash
[user@sahara ~]$ cat
^C
[user@sahara ~]$ 
```

``` bash
[user@sahara ~]$ cat lecture1/messages
cat: lecture1/messages: Is a directory
[user@sahara ~]$ 
```

``` bash
[user@sahara ~]$ cat lecture1/messages/th.txt
สวัสดีชาวโลก
[user@sahara ~]$ 
```

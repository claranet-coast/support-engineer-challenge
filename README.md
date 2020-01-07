# Support Engineer Challenge
These exercises aim to assess the basic skills for Support Engineer role.

## Excercise 1
Write a bash script that takes **three parameters**, two strings and a directory name, and substitutes any occurence of the first string with the second string for any file in the directory, recursively;
  
## Excercise 2
Write a python or bash script that counts the number of script files in a directory subdividing it by the shebang interpreter (i.e. what is after the `#!` in the first line of a file).  
An example output in macOS is:  
```
countexec /usr/bin
81 #!/usr/bin/perl
52 #!/usr/bin/perl5.18
47 #!/bin/sh
44 #!/usr/bin/perl5.28
22 #!/usr/sbin/dtrace -s
...
```
## Excercise 3
Quick! A new wordpress site must go live!  
Automate the setup of the application: create a bash script, ansible playbook or use any tool you like that, when run, download the latest version of wordpress, set it up and configure the webserver to serve the site in a secure, fast and stable manner.  
Do any assumption you need.

## How to share your solution with us
Create your own public GitHub repository, and share the link via mail.  
Feel free to describe your solutions in a readme file.
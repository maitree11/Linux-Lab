# BASIC LINUX COMMANDS 
```bash
>>pwd

```

📌output example:

>/Users/maitree/Linux Lab
>  

## ls command

```bash
>>ls
```

📌Output Examples

```bash
experiment 1.md                         images                                  lab5_2.md
experiment 2.md                         Lab3_exp1.md                            readme.md
image-1.png                             Lab3_exp2.md                            Screenshot 2025-08-21 at 11.03.25.png
image-2.png                             Lab3_exp3.md
image.png                               Lab4_exp1.md
```

### ls flags 

## ls command
The ls command is linux allows to view all the files and folder in current working directory. Flag -a list down all file and folder including the one which are hidden

```bash
>> ls -la
```
📌 Output of ls - la:

```

total 4216
drwxr-xr-x  16 maitree  staff     512 Aug 21 11:08 .
drwxr-x---+ 26 maitree  staff     832 Aug 21 11:09 ..
drwxr-xr-x@ 14 maitree  staff     448 Aug 17 20:48 .git
-rw-r--r--@  1 maitree  staff    2072 Aug 21 10:59 experiment 1.md
-rw-r--r--   1 maitree  staff    2513 Aug 21 10:59 experiment 2.md
-rw-r--r--   1 maitree  staff  844992 Aug 21 11:08 image-1.png
-rw-r--r--   1 maitree  staff  424493 Aug 21 11:08 image-2.png
-rw-r--r--   1 maitree  staff  397614 Aug 21 11:04 image.png
drwxr-xr-x   3 maitree  staff      96 Aug 21 10:58 images
-rw-r--r--   1 maitree  staff    1547 Aug 21 10:59 Lab3_exp1.md
-rw-r--r--   1 maitree  staff    3372 Aug 21 10:59 Lab3_exp2.md
-rw-r--r--   1 maitree  staff    6640 Aug 21 10:59 Lab3_exp3.md
-rw-r--r--   1 maitree  staff    4031 Aug 21 10:59 Lab4_exp1.md
-rw-r--r--@  1 maitree  staff    3076 Aug 21 10:59 lab5_2.md
-rw-r--r--@  1 maitree  staff     224 Aug 17 20:48 readme.md
-rw-r--r--   1 maitree  staff  444663 Aug 21 11:08 Screenshot 2025-08-21 at 11.03.25.png

```
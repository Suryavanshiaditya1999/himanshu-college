 # 20 basic Linux commands 

**1  ls: Lists the contents of a directory.**

```
ls
```

To list even hidden files

```
ls -a
```

to list files in long format 

```
ls -l
```

**2  Changes the current directory.**

```
cd /path/to/directory
```

To get back 

```
cd ..
```

one . reprsents current directory
second . represents parent directory , so you are changing directory from current to parent

**3. pwd: Prints the current working directory.**

```
pwd
```

**4.touch: Creates a new empty file.**

```
touch filename
```

**5.mkdir: Creates a new directory.**

```
mkdir directory_name
```

create a subdirectory 

```
mkdir -p directory_name/sub_directory_name
```

**6.rm: Removes a file or directory**

```
rm filename
```

forcefully remove file

```
rm -rf filename
```

forcefully remove dir

```
rmdir directory_name
```

**7 cp: Copies files or directories.**

```
cp source destination
```

**8 mv: Moves or renames files or directories.**

```
mv source destination
```

**9 cat: Concatenates and displays the content of files.**

```
cat filename
```

**10 echo: Displays a line of text or writes to a file.**

```
echo "Hello, world!"
```

**11 nano: Opens the Nano text editor.**

```
nano filename
```

**12 chmod: Changes file permissions.**

```
chmod 755 filename
```

**13  Changes file owner and group.**

```
chown user:group filename
```

**14 find: Searches for files in a directory hierarchy.**

```
find /path -name filename
```

**15 ps: Displays currently running processes.**

```
grep "pattern" filename
```

**16 ps: Displays currently running processes.**

```
ps
```

**17 top: Displays real-time system statistics**

```
top
```

**18 See disk space**

```
df -h
```




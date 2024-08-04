
### Q. Print `Hello world` in a file and then change world with `universe` 
```
echo "Hello world" >> file.txt
```
```
sed 's/world/universe/' file.txt
```

### Q. Replace the second word in a string


Step 1 write some text in file , use one word that is atleast repeated twice 
```
echo " Hello , this world is a beatufiful world" >> file.txt
```

Step 2 . Use Sed command to replace 2nd word
```
sed 's/world/universe/2' file.txt
```

### Q. Repalce the world globally

```
sed 's/world/universe/g' file.txt
```

## Arguments 

#### Below is an example paragraph

```
Hello students,
Welcome to the Linux course.
This course will cover Linux fundamentals
like file management, process management, and networking.
```

**Change Linux with Unix of 3rd line** 

```
sed '3 s/Linux/Unix/' filename
```

Q. Replace all occurance of course with class .. 

**To make changes permanent**

```
sed -i 's/course/class/g' filename
```

**Delete line containing networking**

```
sed -i '/networking/d' filename
```

**Delete line from range x to y**

```
sed -i '2,3d' filename
```

**Print only the replaced line**

```
sed -n 's/Linux/unix/p' filename
```

**Print only first line**

```
sed -n '1p' filename
```


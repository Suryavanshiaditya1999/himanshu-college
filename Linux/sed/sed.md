
Q. Print `Hello world` in a file and then change world with universe , 
```
echo "Hello world" >> file.txt

sed 's/world/universe/' file.txt
```

Q. Replace the 2nd word

```
echo " Hello , this world is a beatufiful world" >> file.txt
sed 's/world/universe/2' file.txt
```

Q. Repalce the world globally

```
sed 's/world/universe/g' file.txt
```

Q. Replace String on a specific line number , this will replace on 3rd line

```
sed '3 s/world/universe/' file.txt
```

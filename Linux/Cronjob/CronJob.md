# CRONJOB

#### QUESTIONS AND ANSWERS

##### How to create new Cronjob

**Step 1:** Type crontab -e to edit the crontab file.

```
crontab -e
```

**Step 2:** Add your cron job in the format:

```
* * * * * command_to_execute
```

##### To view existing Cronjob

```
crontab -l
```

Q . In your home directory , create a file using echo and in that print hello world every one minute

```
*/1 * * * * echo "Hello world" >> /home/aditya/file.txt
```

Q . lists all files in your home directory and appends the output to a file named file_list.txt every 6 hours

```
0 */6 * * * ls /home/<home_dir>  >> /home/<home_dir>/file_list.txt
```

Same for one minute

```
*/1 * * * * ls /home/<home_dir>  >> /home/<home_dir>/file_list.txt
```



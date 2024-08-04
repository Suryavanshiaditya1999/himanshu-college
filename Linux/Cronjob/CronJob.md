# CRONJOB

## Some Commands and Q & A

### How to create new Cronjob

**Step 1:** Type crontab -e to edit the crontab file.

```
crontab -e
```

**Step 2:** Add your cron job in the format:

```
* * * * * command_to_execute
```

### To view existing Cronjob

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

Q. print "Reminder: Check your email" to a file called reminder.txt in your home directory every day at 9 AM.

```
0 9 * * * echo "Reminder: Check your email" >> /home/<home_dir>/reminder.txt
```

Q. displays the free disk space on your system and saves it to disk_usage.txt every one hour

```
* 1 * * * df -h >> /home/<home_dir>/disk_usage.txt
```

Q . 1 . Create a directory called 'my_dir' in your home directory.
    2. Inside my_dir, create a sub directory 'dir'
    3. Set up a cron job to print "Hello world" to hello.txt every minute.


```
*/1 * * * * mkdir -p /home/<home_dir>/my_dir/dir && echo "Hello world" >> /home/<home_dir>/my_dir/dir/hello.txt
```


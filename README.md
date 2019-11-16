# Execute Linux command at scecific time

#Example 
Remove all files from a directory called filesContainer from Desktop everyday at 23:59

Use this command 
[crontab](https://ss64.com/bash/crontab.html)

```
crontab -e
  
```
Choose editor and add this line

```

59 23 * * * rm -r /home/user/Desktop/filesContainer



* * * * *  [UserName] Command_to_execute
- – – – -
| | | | |
| | | | +—– Day of week (0–7) (Sunday=0 or 7) or Sun, Mon, Tue,…
| | | +———- Month (1–12) or Jan, Feb,…
| | +————-— Day of month (1–31)
| +——————– Hour (0–23)
+————————- Minute (0–59)
  
```

List of entries 

```
# /var/spool/cron/crontabs 

crontab -l
```



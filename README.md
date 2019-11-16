# commandattime
Execute a linux command or script at specific time

#Example 
Remove all files from a directory called filesContainer from Desktop everyday at 23:59

Lauch this command 

```
crontab -e
  
```
Choose editor and add this line

```
59 23 * * * rm -r /home/user/Desktop/filesContainer
  
```

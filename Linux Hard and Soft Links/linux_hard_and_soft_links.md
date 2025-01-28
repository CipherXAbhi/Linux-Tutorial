## What are links?
A connection between a file name and actual data on the disk.

### Soft Link
Link will be removed if original file is deleted or removed.
```l
n -s myfile myfile_link
```
Step1 : you want to know the file path using cat

Step2 : Then use ln command to make a shortcut of the file.

![Screenshot from 2025-01-27 15-07-39](https://github.com/user-attachments/assets/203eb836-1533-46a7-bbe8-1e32f2618f3c)


### Hard Link
Deleting, renaming or removing the original file will not effect the link.
```
ln myfile myfile_hard_link
```
![Screenshot from 2025-01-28 12-06-18](https://github.com/user-attachments/assets/d277fff3-d817-48fa-be7b-c5f612dfe64c)

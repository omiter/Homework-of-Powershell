# Homework-of-Powershell
powershell examples of my blog.

### Invoke-Enumeratefile.ps1

Enumerate all the files under c:\Windows that the permission of NT AUTHORITY\SYSTEM is full control.

We can use the task scheduler to write an arbitrary DACL to the file and then we can modify the files with normal user permissions.

This script will enumerate all the files you can take control over.


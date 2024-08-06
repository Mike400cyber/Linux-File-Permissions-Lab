<h1>Linux File Permissions Lab</h1>

<h2>Description</h2>
In this lab, I ensured the security of the research team's system by checking and updating file permissions within the projects directory on a Linux server. The goal was to align the permissions with the required authorization levels, thereby enhancing the overall security.
<br />


<h2>Languages and Commands Used</h2>

- <b>Bash Shell Scripting</b> 
- <b>ls</b>
- <b>chmod</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Check file and directory details: <br/>
<img src="https://imgur.com/OxTW10y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<h2>ls command</h2>
I used the ls -l command to generate a detailed listing of all files and directories within the "projects" directory. ls -la could also be used to include hidden files and displayed permissions, ownership, and other relevant details for each item. <br />

The output showed one directory (drafts), and four other project files. The permissions were displayed as 10-character strings, representing the access levels for the user, group, and others.
<br />
<br />
<p align="center">
Change file permissions on a hidden file: .project_x.txt <br/>
<img src="https://imgur.com/VZ8BItO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 

<br />
<p align="center">
Change directory permissions: <br/>
<img src="https://imgur.com/qUft8ok.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h2>Summary:</h2>
In this project, I was tasked with updating file and directory permissions within the "projects" directory to align with my organization's security and authorization requirements.
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

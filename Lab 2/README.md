Experiment No. 2
1. Experiment Title
Pushing and Cloning a Repository

2. Aim
Create a local bare remote, push commits to it, and clone a working copy.

3. Software / Tools Required
Visual Studio Code or another text editor
Git and a terminal (for the repository exercises)
A web browser such as Chrome or Edge (for HTML/CSS exercises)
4. Theory
A bare repository stores history without a checked-out working tree and can act as a remote. A remote name such as origin is a shortcut to that location. Push transfers commits to the remote branch; clone creates a separate working copy and retrieves its history, allowing the cloned log to be compared with the original.

5. Program / Queries / Commands
Task 1: Create the bare remote and add origin
git init --bare ../html-remote
git remote add origin ../html-remote
git remote -v
Task 2: Push the current branch
git push origin main
# Use master instead if that is your branch name
git push origin master
Task 3: Clone and inspect history
cd ..
git clone html-remote html-copy
cd html-copy
git log --oneline
Complete source file tracked in the repository: index.html
<!-- Name: SUDHANSHU SINGH| Roll Number: 2510303511 | Assignment: BCS352 Lab 2 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>HTML Lab</title>
</head>
<body>
    <h1>Welcome to My Lab</h1>
    <h2>Next Meeting</h2>
</body>
</html>
6. Input
Task 1
Existing html-lab repository and a local path ../html-remote.


Task 2
Local path html-remote and destination folder html-copy.

7. Output
The following images show the output screenshots already present in the GitHub lab folder:

Task 1
Task 1 output -<img width="847" height="527" alt="image" src="https://github.com/user-attachments/assets/c44faa56-0f28-4bb7-93d2-4a5d69a8f234" />


Task 2
Task 2 output - Lab 2 - Task 2.png



8. Result
The local bare repository is connected as origin, the current branch is pushed, and html-copy is cloned from that remote. The cloned log shows the commits created in the original repository.

9. Viva-Voce Questions
What is a bare repository?
What does the origin remote represent?
How does git clone differ from git init?

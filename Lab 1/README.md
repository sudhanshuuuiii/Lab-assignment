                               Experiment No. 1
1. Experiment Title
Starting a Git Repository

2. Aim
Create a local Git repository, configure repository-specific identity, track an HTML page, and record changes in commits.

3. Software / Tools Required
Visual Studio Code or another text editor
Git and a terminal (for the repository exercises)
A web browser such as Chrome or Edge (for HTML/CSS exercises)

4. Theory
   
Git records file changes in commits. The working tree holds current files, the staging area selects changes for the next commit, and each commit saves a snapshot with a message. Local Git configuration applies only to this repository, so this experiment sets and checks the author identity before tracking the HTML page.


5. Program / Queries / Commands
Task 1: Configure the repository
mkdir html-lab
cd html-lab
git init
git config --local user.name "Your Name"
git config --local user.email "you@example.com"
git config user.name
git config user.email
Task 2: Add and commit the first page
git status
git add index.html
git commit -m "Add home page"
Task 3: Update and commit the page
git add index.html
git commit -m "Add next meeting heading"
git log --oneline
Complete source: index.html

<!-- Name: SUDHANSHU SINGH | Roll Number: 2510303511 | Assignment: BCS352 Lab 1 -->

6. Input

   
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


Task 1
An h1 heading of your choice.
task 1 <img width="891" height="343" alt="image" src="https://github.com/user-attachments/assets/82f9b83f-fdbb-4bc2-88f5-527881c55920" />

Task 2
An h2 heading of your choice.
task 2 <img width="861" height="295" alt="image" src="https://github.com/user-attachments/assets/864fc7fb-d5e2-4366-918e-fe04fe6ea7a6" />

7. Output
The following images show the output screenshots already present in the GitHub lab folder:



8. Result
The html-lab repository is initialized and configured with local author details. index.html is committed first with its home heading and again with the added meeting heading; git log --oneline displays both commits newest-first.


10. Viva-Voce Questions
What is a Git repository?
What is the purpose of staging changes?
What information does git log --oneline show?

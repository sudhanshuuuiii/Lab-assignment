Experiment No. 5
1. Experiment Title
Links and Images

2. Aim
Connect HTML pages with hyperlinks and add an image with useful alternative text.

3. Software / Tools Required
Visual Studio Code or another text editor
Git and a terminal (for the repository exercises)
A web browser such as Chrome or Edge (for HTML/CSS exercises)
4. Theory
Anchors link documents using href, and relative paths point to files based on the current page location. The img element embeds an image resource. Alternative text communicates the image meaning to assistive technologies and provides a fallback if it cannot load; width and height define its rendered dimensions.

5. Program / Queries / Commands
Task 1 — home.html
<!-- Name: SUDHANSHU SINGH | Roll Number: 2510303511 | Assignment: BCS352 Lab 5 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Home</title>
</head>
<body>
    <h1>Welcome to My Site</h1>

    <p>Visit my <a href="portfolio.html">portfolio</a>.</p>
</body>
</html>
Task 2 — portfolio.html
<!-- Name: SUDHANSHU SINGH | Roll Number: 2510303511 | Assignment: BCS352 Lab 5 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Portfolio</title>
</head>
<body>
    <h1>My Portfolio</h1>

    <p><a href="home.html">Back to Home</a></p>
</body>
</html>
Task 3 — portfolio-image.html
<!-- Name: SUDHANSHU SINGH | Roll Number: 2510303511 | Assignment: BCS352 Lab 5 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Portfolio Image</title>
</head>
<body>
    <h1>My Portfolio Image</h1>

    <img src="images/portfolio.jpeg"
         width="200"
         height="200"
         alt="A picture displayed in my portfolio">
</body>
</html>
7. Input
Task 1
Heading and link text from the task.

Task 2
A heading and return-link text of your choice.

Task 3
Instructor-provided image filename and a concise image description for alt text.

7. Output
The following images show the output screenshots already present in the GitHub lab folder:

Task 1
Task 1 output <img width="800" height="417" alt="image" src="https://github.com/user-attachments/assets/586192db-adee-4e66-b3c1-3eef528af830" />


Task 2
Task 2 output - Lab 5 - Task 2.png

Task 3
Task 3 output - Lab 5 - Task 3.png

8. Result
The home and portfolio pages link to one another. The portfolio image page displays the supplied image at 200 by 200 pixels and includes alternative text describing it.

9. Viva-Voce Questions
What does href specify?
Why is alt text important?
What is a relative link?

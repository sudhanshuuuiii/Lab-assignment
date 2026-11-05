Experiment No. 4
1. Experiment Title
Divs, Attributes and a Small Fix

2. Aim
Group page content with div elements, use id and data attributes, and correct malformed HTML.

3. Software / Tools Required
Visual Studio Code or another text editor
Git and a terminal (for the repository exercises)
A web browser such as Chrome or Edge (for HTML/CSS exercises)
4. Theory
Div elements group content for styling or scripting. Classes can be shared across elements, while an id should identify one element. Custom data-* attributes store information in the document without appearing as visible text. Correct nesting and closing tags let the browser build the intended document tree.

5. Program / Queries / Commands
Task 1 — layout.html
<!-- Name: SUDHANSHU SINGH | Roll Number: 2510303511 | Assignment: BCS352 Lab 4 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Page Layout</title>
</head>
<body>
    <div class="header">
        <h1>My Website</h1>
    </div>

    <div class="main">
        <p>This is the main content.</p>
    </div>

    <div class="footer">
        <p>My website footer.</p>
    </div>
</body>
</html>
Task 2 — attributes.html
<!-- Name: SUDHANSHU SINGH | Roll Number: 2510303511 | Assignment: BCS352 Lab 4 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>HTML Attributes</title>
</head>
<body>
    <div id="profile">
        <h1>My Profile</h1>
        <p data-topic="hobbies">My hobbies include reading and listening to music.</p>
    </div>
</body>
</html>
Task 3 — attendence-fixed.html
<!-- Name: SUDHANSHU SINGH | Roll Number: 2510303511 | Assignment: BCS352 Lab 4 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Attendance Record</title>
</head>
<body>
    <h1>Student Attendance</h1>

    <p>Class: B.Tech CSE</p>

    <p>Attendance status: Present</p>
</body>
</html>
6. Input
Task 1
Text for the three layout blocks.

Task 2
Paragraph text; data-topic value hobbies.

Task 3
Supplied broken markup and the names/percentages Asha 92% and Rohan 85%.

7. Output
The following images show the output screenshots already present in the GitHub lab folder:

Task 1
Task 1 output - <img width="694" height="312" alt="image" src="https://github.com/user-attachments/assets/0cbfed3f-d7c3-4c51-ab42-a06607ccdda8" />

Task 2
Task 2 output - Lab 4 - Task 2.png

Task 3
Task 3 output - Lab 4 - Task 3.png

8. Result
The layout page groups header, main, and footer content; the attributes page stores a data-topic value on its paragraph; and the corrected attendance document renders its heading with Asha at 92% and Rohan at 85%.

9. Viva-Voce Questions
How do class and id differ?
Are data-* attributes displayed automatically?
Why should HTML elements be properly nested and closed?

Experiment No. 11
1. Experiment Title
Units and CSS Variables

2. Aim
Use CSS length units and custom properties to define reusable colors and spacing.

3. Software / Tools Required
Visual Studio Code or another text editor
Git and a terminal (for the repository exercises)
A web browser such as Chrome or Edge (for HTML/CSS exercises)
4. Theory
CSS lengths include fixed pixels and relative percent and rem units. Percentages depend on a containing context; rem is based on the root font size. Custom properties beginning with -- can be declared on :root and reused with var(), which keeps colors and spacing consistent across rules.

5. Program / Queries / Commands
Task 1 — units.html
<!-- Name: SUDHANSHU  SINGH| Roll No: 2510303511 | Assignment: BCS352 Lab 11 -->

<!DOCTYPE html>
<html>
<head>
    <title>CSS Units</title>

    <style>
        .pixel-box {
            width: 200px;
            height: 40px;
            background-color: lightblue;
        }

        .percentage-box {
            width: 50%;
            height: 40px;
            background-color: lightgreen;
        }

        p {
            font-size: 1.5rem;
        }
    </style>
</head>
<body>

    <h1>CSS Units Example</h1>

    <div class="pixel-box">200px wide box</div>

    <br>

    <div class="percentage-box">50% wide box</div>

    <p>This paragraph uses 1.5rem font size.</p>

</body>
</html>
Task 2 — variables.html
<!-- Name: SUDHANSHU SINGH | Roll No: 2510303511 | Assignment: BCS352 Lab 11 -->

<!DOCTYPE html>
<html>
<head>
    <title>CSS Variables</title>

    <style>
        :root {
            --main-color: #1d3557;
            --accent-color: #e63946;
            --page-padding: 20px;
        }

        body {
            color: var(--main-color);
            padding: var(--page-padding);
        }

        h1 {
            color: var(--accent-color);
        }
    </style>
</head>
<body>

    <h1>CSS Variables Example</h1>

    <p>
        This page uses CSS variables to control colours and spacing.
    </p>

</body>
</html>
Task 3 — tokens.css
/* Name: LOKESH SHUKLA | Roll No: 2510303281 | Assignment: BCS352 Lab 11 */

:root {
    --primary: #1d3557;
    --accent: #e63946;
    --heading-size: 2rem;
    --spacing: 16px;
}

body {
    color: var(--primary);
    padding: var(--spacing);
}

h1 {
    color: var(--accent);
    font-size: var(--heading-size);
}
6. Input
Task 1
Box dimensions and text values from the task.

Task 2
--main-color #1d3557, --accent-color #e63946, --page-padding 20px.

Task 3
--primary #1d3557, --accent #e63946, --heading-size 2rem, --spacing 16px.

7. Output
The following images show the output screenshots already present in the GitHub lab folder:

 task 1 <img width="520" height="247" alt="image" src="https://github.com/user-attachments/assets/12eb7bf8-5f24-4285-b76d-233f158b556c" />


task 2 <img width="650" height="293" alt="image" src="https://github.com/user-attachments/assets/a730b016-0bfe-4d82-a902-485aff7acad6" />


task 3 <img width="879" height="528" alt="image" src="https://github.com/user-attachments/assets/a0756510-807f-47ab-baaa-800533c15e06" />

8. Result
The examples show a 200px box, a half-width box, and 1.5rem text. CSS custom properties supply reusable page colors, padding, heading color/size, and spacing tokens.

9. Viva-Voce Questions
How does rem differ from px?
What does a percentage width depend on?
How do you use a CSS custom propert

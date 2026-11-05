Experiment No. 10
1. Experiment Title
CSS Fundamentals

2. Aim
Apply inline, internal, and external CSS and use selectors and text styles.

3. Software / Tools Required
Visual Studio Code or another text editor
Git and a terminal (for the repository exercises)
A web browser such as Chrome or Edge (for HTML/CSS exercises)
4. Theory
CSS applies presentation through rules made of selectors and declarations. Element selectors target tags, class selectors use a dot, and id selectors use a hash. Styles may be inline, in an internal style element, or in an external file linked from HTML. The cascade considers importance, specificity, and source order when rules compete.

5. Program / Queries / Commands
Task 1 — inline-internal.html
<!-- Name: SUDHANSHU SINGH | Roll No: 2510303511 | Assignment: BCS352 Lab 10 -->

<!DOCTYPE html>
<html>
<head>
    <title>CSS Styling</title>

    <style>
        h1 {
            color: navy;
        }

        .highlight {
            background-color: yellow;
        }
    </style>
</head>
<body>

    <h1>Welcome to CSS</h1>

    <p style="color: red;">
        This paragraph uses inline CSS.
    </p>

    <p class="highlight">
        This paragraph has a yellow background.
    </p>

</body>
</html>
Task 2 — style.css
/* Name: LOKESH SHUKLA | Roll No: 2510303281 | Assignment: BCS352 Lab 10 */

h1 {
    color: navy;
}

.note {
    font-style: italic;
}

#title {
    text-decoration: underline;
}

p {
    font-size: 18px;
    color: grey;
}
Task 3 — linked.html
<!-- Name: SUDHANSHU SINGH | Roll No: 2510303511 | Assignment: BCS352 Lab 10 -->

<!DOCTYPE html>
<html>
<head>
    <title>External CSS Example</title>

    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1 id="title">My CSS Practice Page</h1>

    <p class="note">
        This is my first paragraph using external CSS.
    </p>

    <p class="note">
        I am learning how to connect CSS with HTML.
    </p>

</body>
</html>
6. Input
Task 1
Heading and paragraph text; class highlight.

Task 2
Specified selectors and styles: navy, italic, underlined, 18px grey paragraphs.

Task 3
Text content and style.css in the same folder.

7. Output
The following images show the output screenshots already present in the GitHub lab folder:

Task 1
task 1 <img width="817" height="342" alt="image" src="https://github.com/user-attachments/assets/b1761a10-a134-4111-910c-78a2375f2f0e" />


Task 2
Task 2 output - Lab 10 - Task 2.png

Task 3
Task 3 output - Lab 10 - Task 3.png

8. Result
The pages demonstrate inline, internal, and external stylesheets. The visible rules give headings navy color, highlight a paragraph yellow, style inline text red, italicize notes, underline the title, and set paragraphs to grey 18px text.

9. Viva-Voce Questions
What is the difference between a class selector and an id selector?
How do you link an external stylesheet?
Which style is written directly on an HTML element?

Experiment No. 15
1. Experiment Title
Responsive Pages with Media Queries

2. Aim
Use mobile-first media queries, responsive images, and rem-based typography.

3. Software / Tools Required
Visual Studio Code or another text editor
Git and a terminal (for the repository exercises)
A web browser such as Chrome or Edge (for HTML/CSS exercises)
4. Theory
Responsive design adapts a page to its viewport. The viewport meta tag sets the layout viewport to the device width. Mobile-first CSS provides a base layout and media queries apply changes at breakpoints. max-width:100% lets an image shrink within its box, height:auto preserves its proportions, and rem units scale text relative to the root font size.

5. Program / Queries / Commands
Task 1 — mobile-first.html
<!-- Name: SUDHANSHU SINGH | Roll No: 2510303511 | Assignment: BCS352 Lab 15 -->

<!DOCTYPE html>
<html>
<head>
    <title>Mobile First Design</title>

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        .cards {
            display: block;
        }

        .card {
            background-color: lightblue;
            border: 2px solid navy;
            padding: 20px;
            margin: 10px;
        }

        @media (min-width: 600px) {
            .cards {
                display: flex;
            }
        }
    </style>
</head>
<body>

    <h1>Mobile First Design</h1>

    <div class="cards">

        <div class="card">
            <h2>Card 1</h2>
            <p>This is the first card.</p>
        </div>

        <div class="card">
            <h2>Card 2</h2>
            <p>This is the second card.</p>
        </div>

    </div>

</body>
</html>
Task 2 — responsive-image.html
<!-- Name: SUDHANSHU SINGH| Roll No: 2510303511 | Assignment: BCS352 Lab 15 -->

<!DOCTYPE html>
<html>
<head>
    <title>Responsive Image</title>

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

    <h1>Responsive Image Example</h1>

    <img src="images/portfolio.jpeg" alt="Portfolio image">

</body>
</html>
Task 3 — responsive-text.html
<!-- Name: LOKESH SHUKLA | Roll No: 2510303281 | Assignment: BCS352 Lab 15 -->

<!DOCTYPE html>
<html>
<head>
    <title>Responsive Text</title>

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            font-size: 1rem;
        }

        h1 {
            font-size: 1.5rem;
        }

        @media (min-width: 600px) {
            h1 {
                font-size: 2.5rem;
            }
        }
    </style>
</head>
<body>

    <h1>Responsive Text Example</h1>

    <p>
        This webpage demonstrates responsive text using CSS media queries.
        The heading size changes according to the screen width.
    </p>

</body>
</html>
6. Input
Task 1
Two card contents and viewport widths below/above 600px.

Task 2
Instructor-provided image file and narrow/wide viewport.

Task 3
Text content and viewport widths below/above 600px.

7. Output
The following images show the output screenshots already present in the GitHub lab folder:

Task 1
Task 1 output - <img width="891" height="475" alt="image" src="https://github.com/user-attachments/assets/301f49a5-33c7-4da0-b3e6-e2300904bc4d" />

Task 1 output -<img width="860" height="461" alt="image" src="https://github.com/user-attachments/assets/16a228ec-3403-4214-8995-96e64086e896" />

Task 2
Task 2 output -<img width="888" height="527" alt="image" src="https://github.com/user-attachments/assets/7e3c8d3e-62c0-4050-994f-ca7caf29e685" />

Task 3
Task 3 output - Lab 15 - Task 3(a).png

Task 3 output - Lab 15 - Task 3(b).png

8. Result
The card layout stacks on phone-sized viewports and changes to side-by-side cards at 600px. The image scales down without distortion, and the heading grows at the 600px breakpoint.

9. Viva-Voce Questions
What is mobile-first design?
What does a media query do?
Why pair max-width: 100% with height: auto for an image?

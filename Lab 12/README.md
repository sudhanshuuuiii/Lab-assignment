Experiment No. 12
1. Experiment Title
Box Model, Cards and Scrolling

2. Aim
Compare box-sizing behavior, style a card, and enable scrolling in a fixed-height container.

3. Software / Tools Required
Visual Studio Code or another text editor
Git and a terminal (for the repository exercises)
A web browser such as Chrome or Edge (for HTML/CSS exercises)
4. Theory
The box model contains content, padding, border, and margin. With content-box, width covers the content only; with border-box, it includes padding and border. Border radius rounds corners. Overflow controls content that exceeds a box, and auto makes excess content scrollable.

6. Program / Queries / Commands
Task 1 — box-model.html
<!-- Name: SUDHANSU SINGH | Roll No: 2510303511| Assignment: BCS352 Lab 12 -->

<!DOCTYPE html>
<html>
<head>
    <title>CSS Box Model</title>

    <style>
        .content-box {
            width: 200px;
            padding: 20px;
            border: 5px solid navy;
            box-sizing: content-box;
            background-color: lightblue;
            margin-bottom: 20px;
        }

        .border-box {
            width: 200px;
            padding: 20px;
            border: 5px solid green;
            box-sizing: border-box;
            background-color: lightgreen;
        }
    </style>
</head>
<body>

    <h1>CSS Box Model Example</h1>

    <div class="content-box">
        Content Box
    </div>

    <div class="border-box">
        Border Box
    </div>

</body>
</html>
Task 2 — card.html
<!-- Name: SUDHANSHU SINGH | Roll No: 2510303511 | Assignment: BCS352 Lab 12 -->

<!DOCTYPE html>
<html>
<head>
    <title>CSS Card Example</title>

    <style>
        .card {
            background-color: lightblue;
            border: 2px solid navy;
            border-radius: 12px;
            padding: 16px;
        }
    </style>
</head>
<body>

    <div class="card">
        <h3>My First Card</h3>
        <p>This is a simple card created using CSS.</p>
    </div>

</body>
</html>
Task 3 — scroll.html
<!-- Name: LOKESH SHUKLA | Roll No: 2510303281 | Assignment: BCS352 Lab 12 -->

<!DOCTYPE html>
<html>
<head>
    <title>CSS Overflow Scroll</title>

    <style>
        .scroll-box {
            height: 120px;
            overflow: auto;
            border: 2px solid navy;
            padding: 10px;
        }
    </style>
</head>
<body>

    <h1>CSS Scroll Example</h1>

    <div class="scroll-box">
        <p>Line 1</p>
        <p>Line 2</p>
        <p>Line 3</p>
        <p>Line 4</p>
        <p>Line 5</p>
    </div>

</body>
</html>
6. Input
Task 1
Width 200px, padding 20px, border 5px.

Task 2
Card heading and paragraph text; specified style values.

Task 3
Five paragraphs labelled Line 1 through Line 5.

7. Output
The following images show the output screenshots already present in the GitHub lab folder:

Task 1
 task 1 <img width="593" height="376" alt="image" src="https://github.com/user-attachments/assets/404c6d20-e1c0-4e8e-8e87-151c65210810" />


Task 2
Task 2 <img width="787" height="355" alt="image" src="https://github.com/user-attachments/assets/edf73656-d820-4f55-90a3-4826bfccec64" />

Task 3
Task 3 output - Lab 12 - Task 3.png

8. Result
The content-box example is wider overall than the border-box example for the same declared width and padding. The card shows a colored background, border and rounded corners; the fixed-height text area scrolls through five lines.

9. Viva-Voce Questions
What does box-sizing: border-box change?
Which CSS property rounds card corners?
When does overflow: auto show a scrollbar?

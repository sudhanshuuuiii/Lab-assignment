Experiment No. 6
1. Experiment Title
Types of HTML Lists

2. Aim
Create unordered, ordered, nested, and description lists.

3. Software / Tools Required
Visual Studio Code or another text editor
Git and a terminal (for the repository exercises)
A web browser such as Chrome or Edge (for HTML/CSS exercises)
4. Theory
Unordered lists show related items without sequence, ordered lists show sequence, and li marks each entry. Lists may nest to express sub-items. Description lists use dl to group terms and explanations, with dt for each term and dd for its description.

5. Program / Queries / Commands
Task 1 — shopping-list.html
<!-- Name: SUDHANSHU SINGH | Roll Number: 2510303511 | Assignment: BCS352 Lab 6 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Shopping List</title>
</head>
<body>
    <h1>Shopping List</h1>

    <ul>
        <li>Notebook</li>
        <li>Pen</li>
        <li>Bag</li>
    </ul>
</body>
</html>
Task 2 — canteen-menu.html
<!-- Name: SUDHANSHU SINGH | Roll Number: 2510303511 | Assignment: BCS352 Lab 6 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Canteen Menu</title>
</head>
<body>
    <h1>Canteen Menu</h1>

    <ol>
        <li>Samosa</li>
        <li>Sandwich
            <ol>
                <li>Cheese</li>
                <li>Vegetable</li>
            </ol>
        </li>
    </ol>
</body>
</html>
Task 3 — faq.html
<!-- Name: SUDHANSHU SINGH | Roll Number: 2510303511 | Assignment: BCS352 Lab 6 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Frequently Asked Questions</title>
</head>
<body>
    <h1>Library FAQ</h1>

    <dl>
        <dt>How many books can I borrow?</dt>
        <dd>You can borrow books according to the library's borrowing rules.</dd>

        <dt>Is the library open on Sunday?</dt>
        <dd>Please check the library's current opening hours.</dd>
    </dl>
</body>
</html>
6. Input
Task 1
Notebook, Pen, Bag.

Task 2
Samosa, Sandwich, Cheese, Vegetable.

Task 3
Questions: “How many books can I borrow?” and “Is the library open on Sunday?”; write an answer for each.

7. Output
The following images show the output screenshots already present in the GitHub lab folder:

Task 1
Task 1 output -<img width="810" height="425" alt="image" src="https://github.com/user-attachments/assets/9ab9f67e-fea2-4d2b-934f-47f2c9ed82c4" />

Task 2
Task 2 output - Lab 6 -<img width="873" height="335" alt="image" src="https://github.com/user-attachments/assets/39d39218-03ca-43db-befa-2829bb686e57" />

Task 3
Task 3 output - Lab 6 - Task 3.png

8. Result
The pages render a three-item shopping list, a numbered canteen menu with nested choices, and two FAQ terms paired with their answers.

9. Viva-Voce Questions
When should you use ul instead of ol?
Which element represents a list item?
What are dt and dd used for?

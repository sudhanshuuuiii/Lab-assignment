Experiment No. 8
1. Experiment Title
Sign-Up Forms and Choices

2. Aim
Create labelled form fields, radio buttons, a dropdown, required fields, and a submit button.

3. Software / Tools Required
Visual Studio Code or another text editor
Git and a terminal (for the repository exercises)
A web browser such as Chrome or Edge (for HTML/CSS exercises)
4. Theory
Forms group controls and specify where/how a submission is sent. Labels should be programmatically associated with inputs through for and id. Input types provide browser behavior suited to their data; radio buttons with the same name form a single-choice group; select and option create a dropdown. The required attribute activates built-in constraint validation.

5. Program / Queries / Commands
Task 1 — signup.html
<!-- Name: SUDHANSHU SINGH | Roll Number: 2510303511 | Assignment: BCS352 Lab 8 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Signup Form</title>
</head>
<body>
    <h1>Signup Form</h1>

    <form method="post" action="thanks.html">

        <label for="full name">Full Name:</label>
        <input type="text" id="fullname" name="fullname">
        <br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email">
        <br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password">
        <br><br>

        <button type="submit">Sign Up</button>

    </form>
</body>
</html>
Task 2 — choices.html
<!-- Name: SUDHANSHU SINGH | Roll Number: 2510303511 | Assignment: BCS352 Lab 8 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Student Choices</title>
</head>
<body>
    <h1>Student Choices</h1>

    <form>
        <p>Select Gender:</p>

        <input type="radio" id="female" name="gender" value="Female">
        <label for="female">Female</label>

        <input type="radio" id="male" name="gender" value="Male">
        <label for="male">Male</label>

        <br><br>

        <label for="course">Select Course:</label>

        <select id="course" name="course">
            <option value="BCA">BCA</option>
            <option value="B.Tech">B.Tech</option>
        </select>

        <br><br>

        <button type="submit">Submit</button>
    </form>
</body>
</html>
Task 3 — signup-required.html
<!-- Name: SUDHANSHU SINGH | Roll Number: 2510303511 | Assignment: BCS352 Lab 8 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Required Signup Form</title>
</head>
<body>
    <h1>Signup Form</h1>

    <form>
        <label for="fullname">Full Name:</label>
        <input
            type="text"
            id="fullname"
            name="fullname"
            placeholder="Enter your full name"
            required
        >

        <br><br>

        <label for="email">Email:</label>
        <input
            type="email"
            id="email"
            name="email"
            required
        >

        <br><br>

        <button type="submit">Submit</button>
    </form>
</body>
</html>
6. Input
Task 1
Name, email, and password entered by the user.

Task 2
One gender choice and one course choice.

Task 3
Name and email values; leave a required field empty to observe validation.

7. Output
The following images show the output screenshots already present in the GitHub lab folder:

Task 1
Task 1 output - <img width="891" height="303" alt="image" src="https://github.com/user-attachments/assets/241f82cc-b67e-454a-8b64-eff1d8a98f89" />

Task 2
Task 2 output -<img width="844" height="408" alt="image" src="https://github.com/user-attachments/assets/001eaff6-2a71-4337-b68f-31c04e1e1f5c" />

Task 3 output - <img width="859" height="431" alt="image" src="https://github.com/user-attachments/assets/b4d95c6c-91f3-46f7-8515-333f173bdff0" />

8. Result
The pages demonstrate labelled name/email/password fields, radio and dropdown choices, and browser validation that prevents submission while a required field is empty.

9. Viva-Voce Questions
Why associate a label with its input?
How do radio buttons make a single-choice group?
What does required do?

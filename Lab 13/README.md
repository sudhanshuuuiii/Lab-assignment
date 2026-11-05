1. Experiment Title
Flexbox Layouts

2. Aim
Use Flexbox to arrange a navigation bar, centered cards, and wrapping product cards.

3. Software / Tools Required
Visual Studio Code or another text editor
Git and a terminal (for the repository exercises)
A web browser such as Chrome or Edge (for HTML/CSS exercises)
4. Theory
Flexbox arranges items along main and cross axes. display:flex creates the container. justify-content aligns or distributes items along the main axis, align-items handles the cross axis, and flex-wrap lets items continue on a new line when space is limited.

5. Program / Queries / Commands
Task 1 — nav-flex.html
<!-- Name: SUDHANSHU SINGH | Roll No: 2510303511 | Assignment: BCS352 Lab 13 -->

<!DOCTYPE html>
<html>
<head>
    <title>Flexbox Navigation</title>

    <style>
        nav {
            display: flex;
            background-color: #333;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 15px 20px;
        }
    </style>
</head>
<body>

    <h1>My Navigation Bar</h1>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Events</a>
        <a href="#">Contact</a>
    </nav>

</body>
</html>
Task 2 — centred-card.html
<!-- Name: SUDHANSHU | Roll No: 2510303511 | Assignment: BCS352 Lab 13 -->

<!DOCTYPE html>
<html>
<head>
    <title>Centered Cards</title>

    <style>
        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
            min-height: 300px;
        }

        .card {
            background-color: lightblue;
            border: 2px solid navy;
            padding: 20px;
            width: 150px;
            text-align: center;
        }
    </style>
</head>
<body>

    <h1>Pricing Plans</h1>

    <div class="container">
        <div class="card">
            <h2>Starter</h2>
            <p>₹199</p>
        </div>

        <div class="card">
            <h2>Standard</h2>
            <p>₹349</p>
        </div>

        <div class="card">
            <h2>Premium</h2>
            <p>₹499</p>
        </div>
    </div>

</body>
</html>
Task 3 — wrapping-cards.html
<!-- Name: SUDHANSHU SINGH | Roll No: 2510303511 | Assignment: BCS352 Lab 13 -->

<!DOCTYPE html>
<html>
<head>
    <title>Flexbox Wrapping Cards</title>

    <style>
        .container {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
        }

        .card {
            width: 180px;
            padding: 15px;
            border: 2px solid navy;
            background-color: lightblue;
            text-align: center;
        }
    </style>
</head>
<body>

    <h1>Stationery Shop</h1>

    <div class="container">
        <div class="card">
            <h2>Notebook</h2>
            <p>₹60</p>
        </div>

        <div class="card">
            <h2>Pen</h2>
            <p>₹15</p>
        </div>

        <div class="card">
            <h2>Bag</h2>
            <p>₹350</p>
        </div>

        <div class="card">
            <h2>Book</h2>
            <p>₹120</p>
        </div>
    </div>

</body>
</html>
6. Input
Task 1
Home, About, Events, Contact.

Task 2
Starter 199, Standard 349, Premium 499.

Task 3
Notebook 60, Pen 15, Bag 350, Book 120; narrow browser viewport.

7. Output
The following images show the output screenshots already present in the GitHub lab folder:

Task 1
<img width="785" height="319" alt="image" src="https://github.com/user-attachments/assets/9a415810-defc-47f3-9c57-2ed81e9cc6cf" />

Task 2
<img width="757" height="305" alt="image" src="https://github.com/user-attachments/assets/15f7642d-9bb9-44c0-a80a-e0eb2f3a3a50" />


Task 3
<img width="754" height="321" alt="image" src="https://github.com/user-attachments/assets/c090c581-0a5e-4e37-8ae9-275386783ea8" />


Task 3 output - Lab 13 - Task 3(b).png

8. Result
The navigation links form a horizontal dark flex bar, the three pricing cards are centered in a row, and the stationery cards wrap to additional rows at a narrower viewport.

9. Viva-Voce Questions
How do you create a flex container?
What does justify-content control?
What does flex-wrap: wrap allow?

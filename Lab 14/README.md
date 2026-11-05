Experiment No. 14
1. Experiment Title
CSS Grid Layouts

2. Aim
Create equal-column grids, a responsive gallery, and a named-area page layout.

3. Software / Tools Required
Visual Studio Code or another text editor
Git and a terminal (for the repository exercises)
A web browser such as Chrome or Edge (for HTML/CSS exercises)
4. Theory
CSS Grid arranges content in two dimensions. The fr unit shares available track space; repeat() expresses repeated tracks; minmax() sets track size limits; and auto-fill fits as many tracks as possible. Named grid-template-areas describe page regions and assign elements to those regions.

5. Program / Queries / Commands
Task 1 — grid-first.html
<!-- Name: SUDHANSHU SINGH | Roll No: 2510303511 | Assignment: BCS352 Lab 14 -->

<!DOCTYPE html>
<html>
<head>
    <title>First CSS Grid</title>

    <style>
        .container {
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            gap: 12px;
        }

        .box {
            background-color: lightblue;
            border: 2px solid navy;
            padding: 30px;
            text-align: center;
        }
    </style>
</head>
<body>

    <h1>CSS Grid Example</h1>

    <div class="container">
        <div class="box">1</div>
        <div class="box">2</div>
        <div class="box">3</div>
        <div class="box">4</div>
        <div class="box">5</div>
        <div class="box">6</div>
    </div>

</body>
</html>
Task 2 — gallery.html
<!-- Name: SUDHANSHU SINGH | Roll No: 2510303511 | Assignment: BCS352 Lab 14 -->

<!DOCTYPE html>
<html>
<head>
    <title>Club Photo Gallery</title>

    <style>
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
            gap: 10px;
        }

        .photo {
            background-color: lightblue;
            border: 2px solid navy;
            padding: 30px;
            text-align: center;
        }
    </style>
</head>
<body>

    <h1>Club Photo Gallery</h1>

    <div class="gallery">
        <div class="photo">Photo 1</div>
        <div class="photo">Photo 2</div>
        <div class="photo">Photo 3</div>
        <div class="photo">Photo 4</div>
        <div class="photo">Photo 5</div>
        <div class="photo">Photo 6</div>
    </div>

</body>
</html>
Task 3 — dashboard-areas.html
<!-- Name: SUDHANSHU SINGH | Roll No: 2510303511| Assignment: BCS352 Lab 14 -->

<!DOCTYPE html>
<html>
<head>
    <title>Dashboard Grid Areas</title>

    <style>
        .dashboard {
            display: grid;
            grid-template-columns: 200px 1fr;
            grid-template-areas:
                "header header"
                "sidebar main"
                "footer footer";
            gap: 10px;
        }

        .header {
            grid-area: header;
            background-color: navy;
            color: white;
            padding: 20px;
        }

        .sidebar {
            grid-area: sidebar;
            background-color: lightblue;
            padding: 20px;
        }

        .main {
            grid-area: main;
            background-color: lightgreen;
            padding: 20px;
        }

        .footer {
            grid-area: footer;
            background-color: lightgray;
            padding: 20px;
        }
    </style>
</head>
<body>

    <h1>My Dashboard</h1>

    <div class="dashboard">

        <div class="header">
            Header
        </div>

        <div class="sidebar">
            Sidebar
        </div>

        <div class="main">
            Main Content
        </div>

        <div class="footer">
            Footer
        </div>

    </div>

</body>
</html>
6. Input
Task 1
Numbers 1–6; three equal columns.

Task 2
Photo 1 through Photo 6; minimum track width 150px.

Task 3
Two columns, 200px and 1fr; named layout regions.

7. Output
The following images show the output screenshots already present in the GitHub lab folder:

Task 1
Task 1 output - Lab 14 - Task 1.png

Task 2
Task 2 output - Lab 14 - Task 2(a).png

Task 2 output - Lab 14 - Task 2(b).png

Task 3
Task 3 output - Lab 14 - Task 3.png

8. Result
The grid page displays six boxes in three columns, the gallery fits columns according to available width, and the named-area dashboard places a header and footer across the page with sidebar and main content beneath.

9. Viva-Voce Questions
What does fr represent in CSS Grid?
What does minmax() define?
How do grid-template-areas help describe a layout?

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Web Page</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Navigation Bar */
        .navbar {
            background-color: #333;
            overflow: hidden;
        }

        .navbar a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }

        .navbar a:hover {
            background-color: #575757;
        }

        /* Container */
        .container {
            padding: 20px;
        }

        /* Image */
        .hero-image {
            width: 100%;
            max-height: 300px;
            object-fit: cover;
        }

        /* Table */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 10px;
            text-align: left;
        }

        th {
            background-color: #f4f4f4;
        }
    </style>
</head>

<body>

    <!-- Navigation Bar -->
    <div class="navbar">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact Us</a>
    </div>

    <!-- Main Content -->
    <div class="container">

        <!-- Image -->
        <img src="Istoragelemulated/0/Download/iStock-1998218882-scaled.jpg" alt="Banner Image" class="hero-image">

        <!-- Student Table -->
        <h2>Student Data</h2>

        <table>
            <tr>
                <th>Student Name</th>
                <th>Student Class</th>
                <th>Student Grade</th>
            </tr>
            <tr>
                <td>Alice Johnson</td>
                <td>10</td>
                <td>A</td>
            </tr>
            <tr>
                <td>Michael Smith</td>
                <td>9</td>
                <td>B+</td>
            </tr>
            <tr>
                <td>Sarah Williams</td>
                <td>11</td>
                <td>A-</td>
            </tr>
        </table>

    </div>

</body>
</html>

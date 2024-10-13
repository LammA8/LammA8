<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taeash</title>
    <style>
        :root {
            --primary-color: #105b58;
            --background-color: #f5f5f5;
            --card-background: #e6e6e6;
            --text-color: white;
            --border-color: #ddd;
        }

        body {
            font-family: Arial, sans-serif;
            margin: 1;
            padding: 1;
            background-color: var(--background-color);
            direction: rtl; /* Set direction to right-to-left */
        }

        /* Header Section */
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: var(--primary-color);
            padding: 10px 20px;
            color: var(--text-color);
        }

        /* Navbar on the left */
        nav {
            display: flex;
            gap: 40px; /* Increased gap for spacing */
            font-size: 20px; /* Increased font size */
            margin-right: auto; /* Push the navbar contents to the left */
        }

        nav a {
            color: var(--text-color);
            text-decoration: none;
            padding: 15px 30px; /* Increased padding for larger clickable area */
        }

        /* Main Content Container */
        .main-content-container {
            display: flex;
            justify-content: center;
            padding: 30px;
            margin-top: 60px; /* To avoid overlap with the header */
        }

        /* Main Content */
        .main-content {
            width: 60%;
            background-color: #fff;
            padding: 20px;
            position: relative; /* Position relative for border */
        }

        /* Inner Border */
        .inner-border {
            border: 1px solid var(--border-color);
            border-radius: 5px;
            padding: 20px; /* Padding inside the border */
        }

        .main-content h2 {
            font-size: 25px;
            color: var(--primary-color);
            margin-bottom: 20px;
            text-align: center;
        }

        .card-container {
            display: flex;
            justify-content: center; /* Center the cards */
            flex-wrap: wrap; /* Allow cards to wrap to the next line */
        }

        .card {
            width: 200px; /* Fixed width for cards */
            padding: 15px;
            margin: 12px;
            background-color: var(--card-background);
            border-radius: 8px;
            text-align: center;
            border: 1px solid #ccc;
        }

        /* Footer Section */
        .footer {
            text-align: center;
            margin-top: 60px; /* Space above the footer */
            padding: 15px;
            background-color: #105b58; /* Footer background color */
            color: var(--text-color); /* Text color for footer */
        }

        .footer h3 {
            margin: 10px 1;
        }

        .footer p {
            margin: 5px 1;
            color: #fff; /* Text color for footer paragraphs */
        }

        @media (max-width: 768px) {
            .main-content {
                width: 86%;
            }
            .card {
                width: 90%; /* Make cards full width on smaller screens */
                margin: 5px 1;
            }
        }
        
        #Layer1 {
            position: absolute;
            width: 220px;
            height: 220px;
            z-index: 1;
            left: 84px;
            top: 485px;
        }
    </style>
</head>
<body>

<!-- Header Section -->
<div class="header">
    <!-- Navbar on the left -->
    <nav>
        <!-- Removed BMI Calc -->
        <a href="#">Psychological Awareness</a>
        <a href="#">Login</a>
        <a href="#">HomePage</a>
    </nav>
</div>

<!-- Main Content in the Center -->
<div class="main-content-container">
    <div class="main-content">
        <div class="inner-border">
            <h2>Diseases list</h2>
            <div class="card-container">
                <div class="card">Diabetes</div>
                <div class="card">Hypertension</div>
                <div class="card">Alzheimer</div>
            </div>
        </div>
    </div>
</div>

<!-- Footer Section for Contact and About Us -->
<div class="footer">
    <h3>:Contact References</h3>
    <p>Email: TaeashSite@hotmail.com</p>
    <p>X platform: <a href="https://x.com/TaeashSite" style="color: #fff; text-decoration: underline;">https://x.com/TaeashSite</a></p>
    
    <h3>About Us</h3>
    <p>.We are dedicated to providing health-related resources and information</p>
</div>

<div id="Layer1"><img src="imagelogo.PNG" width="204" height="212"></div>
</body>
</html>

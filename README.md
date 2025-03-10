<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Styling Example</title>
    <style>
        /* CSS Code */
        
        /* Body styling */
        body {
            font-family: Arial, sans-serif; /* Sets font for the whole page */
            background-color: #f4f4f9; /* Light gray background */
            margin: 0;
            padding: 0;
        }

        /* Header styling */
        header {
            background-color: #4CAF50; /* Green background */
            color: white; /* White text color */
            text-align: center;
            padding: 20px;
        }

        /* Main content section styling */
        .content {
            margin: 20px;
            padding: 20px;
            background-color: white; /* White background for content */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Light shadow for effect */
        }

        /* Button styling */
        .button {
            background-color: #008CBA; /* Blue background */
            color: white;
            padding: 15px 25px;
            text-align: center;
            text-decoration: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            display: inline-block;
            transition: background-color 0.3s ease;
        }

        /* Button hover effect */
        .button:hover {
            background-color: #005f73; /* Darker blue when hovered */
        }

        /* Footer styling */
        footer {
            background-color: #333; /* Dark background */
            color: white;
            text-align: center;
            padding: 10px;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Webpage</h1>
    </header>

    <div class="content">
        <h2>This is the main content</h2>
        <p>This webpage is styled using CSS to make it visually appealing.</p>
        <a href="#" class="button">Click Me!</a>
    </div>

    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>

</body>
</html>



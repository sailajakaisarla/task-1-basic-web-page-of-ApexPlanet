# task-1-basic-web-page-of-ApexPlanet
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Simple Webpage</title>
    <style>
        /* CSS Styling */

        body {
            font-family: Arial, sans-serif; /* Font style */
            background-color: #f0f8ff; /* Light blue background */
            color: #333; /* Dark gray text */
            margin: 20px;
            line-height: 1.6;
        }

        h1 {
            color: #2e8b57; /* Sea green */
            text-align: center;
        }

        h2 {
            color: #4682b4; /* Steel blue */
            margin-top: 40px;
        }

        p {
            margin: 15px 0;
        }

        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 15px 0;
            border-radius: 8px;
        }

        a {
            color: #d2691e; /* Chocolate */
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Layout adjustment: container for content */
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #ffffff; /* White background for content area */
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 8px;
        }

        /* Style for the button */
        button {
            display: inline-block;
            padding: 10px 20px;
            margin-top: 20px;
            font-size: 16px;
            background-color: #4CAF50; /* Green */
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to My Webpage</h1>
        <p><strong>NATURE</strong> is the art of God.Keep your face always toward the sunshine, and shadows will fall behind you.</p>
        
        <h2>My Favorite Image</h2>
        <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Beautiful Landscape" />

        <p>Visit <a href="https://www.google.com" target="_blank" rel="noopener noreferrer">OpenGOOGLE</a> to learn and know more about the world.</p>

        <button id="alertButton">Click Me!</button>
    </div>

    <script>
        // JavaScript to add interaction
        document.getElementById('alertButton').addEventListener('click', function() {
            alert('Button was clicked! Hello there!');
        });
    </script>
</body>
</html>

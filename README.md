<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Finance</title>
    <style>
        body {
            margin: 0;
            font-family: sans-serif;
            background-color: #000; /* Black background */
            color: #fff; /* White text */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            flex-direction: column;
            position: relative; /* For absolute positioning of the button */
        }

        .container {
            display: flex;
            align-items: center;
        }

        .text {
            font-size: 5em;
            font-weight: bold;
            margin-right: 50px; /* Space between text and image */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5); /* Optional text shadow */
        }

        .image-container {
            /* You might want to add some styling to control the image size */
        }

        img {
            max-width: 500px; /* Adjust as needed */
            height: auto;
        }

        .next-button {
            position: absolute;
            bottom: 20px;
            left: 20px;
            padding: 10px 20px;
            background-color: #f00; /* Red background */
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.2em;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3); /* Optional shadow */
        }

        .next-button:hover {
            background-color: #d00; /* Darker red on hover */
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="text">Personal<br>Finance</div>
        <div class="image-container">
            <img src="your-image.jpg" alt="Penny Jar">
        </div>
    </div>
    <button class="next-button">Next</button>

    <script>
        // You can add JavaScript functionality to the "Next" button here
        const nextButton = document.querySelector('.next-button');
        nextButton.addEventListener('click', () => {
            alert('Next button clicked!'); // Example action
            // You can redirect to another page or perform other actions
        });
    </script>
</body>
</html>

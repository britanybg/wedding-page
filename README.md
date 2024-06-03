<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Britany's Wedding Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #e0f7e9;
            text-align: center;
            padding: 50px 0;
            border-bottom: 2px solid #ccc;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
            color: #2e8b57;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #2e8b57;
        }
        .floral-bg {
            background-image: url('https://www.example.com/floral-background.jpg');
            background-size: cover;
            background-position: center;
            padding: 40px;
            border-radius: 8px;
        }
        .content {
            max-width: 800px;
            margin: 0 auto;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #e0f7e9;
            border-top: 2px solid #ccc;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our Wedding Webpage</h1>
    </header>

    <section id="date-time" class="floral-bg">
        <div class="content">
            <h2>Date and Time Details</h2>
            <p>Join us for our wedding celebration on:</p>
            <p><strong>Date:</strong> July 20, 2024</p>
            <p><strong>Time:</strong> 4:00 PM</p>
            <p><strong>Venue:</strong> The Green Gardens, Springfield</p>
        </div>
    </section>

    <section id="wedding-gifts">
        <div class="content">
            <h2>Wedding Gift Ideas</h2>
            <p>Your presence at our wedding is the greatest gift of all. However, if you wish to honor us with a gift, we have created a registry at the following stores:</p>
            <ul>
                <li><a href="https://www.example.com/store1">Store 1</a></li>
                <li><a href="https://www.example.com/store2">Store 2</a></li>
                <li><a href="https://www.example.com/store3">Store 3</a></li>
            </ul>
        </div>
    </section>

    <section id="share-memories">
        <div class="content">
            <h2>Share Your Memories with Us</h2>
            <p>We would love to see the moments you've captured. Please share your photos and messages with us using the hashtag <strong>#BritanyWedding2024</strong> on social media or upload them directly here:</p>
            <form>
                <label for="memory">Your Message:</label><br>
                <textarea id="memory" name="memory" rows="4" cols="50" placeholder="Share your message..."></textarea><br>
                <label for="photo">Upload Photo:</label><br>
                <input type="file" id="photo" name="photo"><br><br>
                <input type="submit" value="Submit">
            </form>
        </div>
    </section>

    <section id="journey">
        <div class="content">
            <h2>Our Journey</h2>
            <p>From our first meeting to this special day, our journey has been filled with love and adventure. We can't wait to start this new chapter together and are thrilled to have you with us.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Britany's Wedding Webpage. All rights reserved.</p>
    </footer>
</body>
</html>

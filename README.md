<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Welcome to RD CHANNLE.WEB, the best place for awesome content!">
    <meta name="google-site-verification" content="PQbuw-1Tf9SmwQJ8sbzrOoU1jq4GB1oGswZkxe_p3dg" />
    <title>RD CHANNLE.WEB</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f0f0f0;
        }
        header {
            background: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        header img {
            height: 100px;
        }
        .nav {
            margin-top: 10px;
        }
        .nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            display: inline-block;
        }
        .nav a:hover {
            background: #555;
        }
        .button {
            background: #007bff;
            color: #fff;
            border: none;
            padding: 15px;
            border-radius: 5px;
            font-size: 18px;
            text-decoration: none;
            display: inline-block;
            transition: background 0.3s;
        }
        .button:hover {
            background: #0056b3;
        }
        .page {
            padding: 20px;
        }
        .video-section {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .video-section .card {
            background: #f4f4f4;
            border-radius: 10px;
            overflow: hidden;
            width: 300px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .video-section .card iframe {
            width: 100%;
            height: 200px;
        }
        .video-section .card h3 {
            font-size: 18px;
            margin: 10px 0;
        }
        .video-section .card p {
            padding: 0 10px;
        }
        .about-content {
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
        }
        .problems {
            background: #ffffff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }
        .problems h2 {
            font-size: 24px;
            color: #333;
            margin-bottom: 20px;
        }
        .problems form {
            display: flex;
            flex-direction: column;
        }
        .problems form input[type="text"],
        .problems form textarea {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 16px;
        }
        .problems form button {
            background: #007bff;
            color: #fff;
            border: none;
            padding: 15px;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
            transition: background 0.3s;
        }
        .problems form button:hover {
            background: #0056b3;
        }
        .problems .answers {
            margin-top: 20px;
        }
        .problems .answer {
            background: #f9f9f9;
            padding: 10px;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        /* Animation Styles */
        .animation-container {
            text-align: center;
            margin-top: 20px;
        }
        .animation-container h2 {
            font-size: 28px;
            color: #007bff;
            margin-bottom: 20px;
        }
        .animation-container .subscribe-animation {
            display: inline-block;
            font-size: 24px;
            color: #007bff;
            font-weight: bold;
            position: relative;
            animation: rotate 2s linear infinite;
        }
        @keyframes rotate {
            0% {
                transform: rotate(0deg);
            }
            100% {
                transform: rotate(360deg);
            }
        }
        #fireworks {
            width: 100%;
            height: 400px;
            background-image: url('https://example.com/fireworks.gif');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
            margin-top: 20px;
        }
        /* Colorful Background for Home */
        #home {
            background: linear-gradient(135deg, #ff8a00, #e52e71);
            color: #fff;
            text-align: center;
            padding: 100px 20px;
            position: relative;
        }
        #home h1 {
            font-size: 3em;
            margin: 0;
        }
        #home p {
            font-size: 1.5em;
            margin: 20px 0;
        }
        .button-container {
            margin-top: 20px;
        }
        .button-container .button {
            margin: 0;
        }
        /* Additional Styles for About Page */
        #about {
            background: #fff;
            padding: 40px 20px;
            color: #333;
        }
        #about h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }
        #about p {
            font-size: 1.2em;
            line-height: 1.6;
        }
        /* Style for the Problem Page */
        #problems {
            background: #fff;
            padding: 40px 20px;
        }
        #problems .problems {
            max-width: 800px;
            margin: 0 auto;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://yt3.ggpht.com/5DVYp87T9kqPiwPVOW9H1rc-4JjD4D9q4nLaFdwJ88m1tHzUeMAH8pcjCUzpdzebjqFHRM1QgEg=s176-c-k-c0x00ffffff-no-rj" alt="RD CHANNLE Logo">
        <div class="nav">
            <a href="#" onclick="showPage('home')">Home</a>
            <a href="#" onclick="showPage('videos')">Videos</a>
            <a href="#" onclick="showPage('about')">About</a>
            <a href="#" onclick="showPage('problems')">Problems</a>
            <a href="https://www.youtube.com/channel/UCpJ90x2kTe14fpkx4cogWAQ" class="button" target="_blank">Channel</a>
        </div>
    </header>
    
    <main>
        <!-- Home Page Content -->
        <div id="home" class="page">
            <h1>Welcome to RD CHANNLE.WEB!</h1>
            <p>Explore our channel for amazing content. Don't forget to subscribe!</p>
            <!-- Fireworks Animation -->
            <div id="fireworks"></div>
            <div class="animation-container">
                <h2>Don't Miss Out!</h2>
                <div class="subscribe-animation">
                    <span>Subscribe to our channel!</span>
                </div>
            </div>
            <!-- Channel Button -->
            <div class="button-container">
                <a href="https://www.youtube.com/channel/UCpJ90x2kTe14fpkx4cogWAQ" class="button" target="_blank">Visit Our Channel</a>
            </div>
        </div>

        <!-- Videos Page Content -->
        <div id="videos" class="page" style="display:none;">
            <div class="video-section">
                <div class="card">
                    <iframe src="https://www.youtube.com/embed/SF-1rZy4Pn4" allowfullscreen></iframe>
                    <h3>Video Title 1</h3>
                    <p>Description of the first video.</p>
                    <a href="https://youtu.be/SF-1rZy4Pn4" class="button" target="_blank">Watch on YouTube</a>
                </div>
                <div class="card">
                    <iframe src="https://www.youtube.com/embed/gkl2UWlwdXk" allowfullscreen></iframe>
                    <h3>Video Title 2</h3>
                    <p>Description of the second video.</p>
                    <a href="https://youtu.be/gkl2UWlwdXk" class="button" target="_blank">Watch on YouTube</a>
                </div>
                <div class="card">
                    <iframe src="https://www.youtube.com/embed/Y_zAE--HNzk" allowfullscreen></iframe>
                    <h3>Video Title 3</h3>
                    <p>Description of the third video.</p>
                    <a href="https://youtu.be/Y_zAE--HNzk" class="button" target="_blank">Watch on YouTube</a>
                </div>
                <div class="card">
                    <iframe src="https://www.youtube.com/embed/jNpCOmfdlQQ" allowfullscreen></iframe>
                    <h3>Video Title 4</h3>
                    <p>Description of the fourth video.</p>
                    <a href="https://youtu.be/jNpCOmfdlQQ" class="button" target="_blank">Watch on YouTube</a>
                </div>
                <div class="card">
                    <iframe src="https://www.youtube.com/embed/QA_mfUhy_q8" allowfullscreen></iframe>
                    <h3>Video Title 5</h3>
                    <p>Description of the fifth video.</p>
                    <a href="https://youtu.be/QA_mfUhy_q8" class="button" target="_blank">Watch on YouTube</a>
                </div>
                <div class="card">
                    <iframe src="https://www.youtube.com/embed/fRrqI3OJeFU" allowfullscreen></iframe>
                    <h3>Video Title 6</h3>
                    <p>Description of the sixth video.</p>
                    <a href="https://youtu.be/fRrqI3OJeFU" class="button" target="_blank">Watch on YouTube</a>
                </div>
                <div class="card">
                    <iframe src="https://www.youtube.com/embed/bFxvV6ySWTA" allowfullscreen></iframe>
                    <h3>Video Title 7</h3>
                    <p>Description of the seventh video.</p>
                    <a href="https://youtu.be/bFxvV6ySWTA" class="button" target="_blank">Watch on YouTube</a>
                </div>
                <div class="card">
                    <iframe src="https://www.youtube.com/embed/cHZTbrwlaBM" allowfullscreen></iframe>
                    <h3>Video Title 8</h3>
                    <p>Description of the eighth video.</p>
                    <a href="https://youtu.be/cHZTbrwlaBM" class="button" target="_blank">Watch on YouTube</a>
                </div>
            </div>
        </div>

        <!-- About Page Content -->
        <div id="about" class="page" style="display:none;">
            <div class="about-content">
                <h2>About RD CHANNLE</h2>
                <p>RD CHANNLE is your go-to place for engaging and entertaining content. Our channel provides a variety of videos that cater to different interests and tastes. From gaming to tutorials and beyond, there's something for everyone. Stay tuned for more amazing content and make sure to subscribe to never miss an update!</p>
            </div>
        </div>

        <!-- Problems Page Content -->
        <div id="problems" class="page" style="display:none;">
            <div class="problems">
                <h2>Have Questions?</h2>
                <form id="question-form">
                    <input type="text" name="name" placeholder="Your Name" required>
                    <input type="text" name="email" placeholder="Your Email" required>
                    <textarea name="question" placeholder="Your Question" rows="5" required></textarea>
                    <button type="submit">Submit</button>
                </form>
                <div class="answers">
                    <!-- Example answer, dynamically generated -->
                    <div class="answer">
                        <strong>Question 1:</strong> How do I submit a question?<br>
                        <strong>Answer:</strong> Use the form above to submit your question.
                    </div>
                </div>
            </div>
        </div>
    </main>

    <script>
        function showPage(pageId) {
            document.querySelectorAll('.page').forEach(function(page) {
                page.style.display = 'none';
            });
            document.getElementById(pageId).style.display = 'block';
        }

        // Initialize to show home page
        showPage('home');
    </script>
</body>
</html>

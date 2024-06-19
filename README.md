html_content = """
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rahil's Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 2em auto;
            padding: 0 1em;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .content {
            padding: 2em;
        }
        h1, h2 {
            color: #333;
        }
        p {
            color: #666;
        }
        a {
            color: #007BFF;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .social-links a {
            margin: 0 10px;
            color: #007BFF;
            text-decoration: none;
        }
        .social-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Rahil</h1>
        <p>Computer Engineering Student | Social Designer | Artist</p>
    </header>
    <div class="container">
        <div class="content">
            <h2>About Me</h2>
            <p>Hi, I am Rahil, a student of Computer Engineering at the Sharif University of Technology International campus, and a Social Designer. I am curious and creative, passionate about nature and animals, especially cats! I enjoy immersing myself in different cultures while traveling, getting lost in books and movies, and expressing myself through art and photography.</p>
            <p>I appreciate the little things in life. I love cooking, and trying new sports. I am usually up for a good conversation.</p>
            
            <h2>Contact Me</h2>
            <p>Feel free to reach out to me on social media or via email. I'd love to connect!</p>
            <div class="social-links">
                <a href="https://www.instagram.com/_rahil._.tvk_/" target="_blank">Instagram</a> |
                <a href="https://www.linkedin.com/in/your-linkedin-profile" target="_blank">LinkedIn</a> |
                <a href="https://t.me/aworkpage" target="_blank">Telegram</a> |
                <a href="mailto:ar.workpage@gmail.com">Email</a>
            </div>
        </div>
    </div>
</body>
</html>
"""

with open("Rahil_webpage.html", "w") as file:
    file.write(html_content)

print("HTML file has been created successfully.")

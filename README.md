<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sumit Jadhav | GitHub Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #ffffff;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            flex-direction: column;
        }

        .container {
            background-color: #1f1f1f;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 800px;
            text-align: center;
        }

        h1, h2 {
            color: #ffffff;
        }

        .details, .social-links {
            list-style-type: none;
            padding: 0;
        }

        .details li {
            margin: 10px 0;
        }

        .social-links li {
            display: inline;
            margin-right: 15px;
        }

        .social-links a {
            text-decoration: none;
            color: #00e6e6;
        }

        .social-links a:hover {
            text-decoration: underline;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 10px;
            justify-content: center;
        }

        .skills img {
            width: 50px;
            height: 50px;
            transition: transform 0.2s;
        }

        .skills img:hover {
            transform: scale(1.1);
        }

        .stats-container {
            display: flex;
            justify-content: space-around;
            margin-top: 30px;
            flex-wrap: wrap;
        }

        .stats-box {
            background-color: #292929;
            border-radius: 10px;
            padding: 20px;
            margin: 10px;
            text-align: center;
            flex: 1;
            min-width: 280px;
        }

        .banner img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="banner">
            <img src="images/android_developer_banner.png" alt="Android Developer Banner">
        </div>

        <h1>Hi 👋, I'm Sumit Jadhav</h1>
        <p>A passionate Full-Stack developer</p>

        <ul class="details">
            <li>👋 Hi, I’m Sumit Jadhav</li>
            <li>👀 I’m interested in Full Stack Development</li>
            <li>🌱 I’m currently learning <strong>React Native</strong> for Android development</li>
            <li>💞️ I’m looking to collaborate on App Development</li>
            <li>📫 Connect With me on My Gmail: <a href="mailto:sumitjadhav6067@gmail.com">sumitjadhav6067@gmail.com</a></li>
            <li>⚡ Fun fact: I also play video games</li>
        </ul>

        <h2>Connect with me:</h2>
        <ul class="social-links">
            <li><a href="https://github.com/Victorsward32" target="_blank">GitHub</a></li>
            <li><a href="https://www.linkedin.com/in/sumit-jadhav-a51894157/" target="_blank">LinkedIn</a></li>
            <li><a href="https://medium.com/@sumitjadhav6067" target="_blank">Medium</a></li>
            <li><a href="https://www.hackerrank.com/profile/sumitjadhav6067" target="_blank">HackerRank</a></li>
        </ul>

        <div class="stats-container">
            <div class="stats-box">
                <h3>Most Used Languages</h3>
                <img src="images/languages_chart.png" alt="Languages Chart" style="width:100%;">
            </div>
        </div>

        <h2>Languages:</h2>
        <div class="skills">
            <img src="images/python.png" alt="Python">
            <img src="images/java.png" alt="Java">
            <img src="images/html.png" alt="HTML">
            <img src="images/css.png" alt="CSS">
            <img src="images/javascript.png" alt="JavaScript">
            <img src="images/sql.png" alt="SQL">
            <img src="images/xml.png" alt="XML">
            <img src="images/mongodb.png" alt="MongoDB">
        </div>

        <h2>Tools:</h2>
        <div class="skills">
            <img src="images/android_studio.png" alt="Android Studio">
            <img src="images/vscode.png" alt="VS Code">
            <img src="images/git.png" alt="Git">
            <img src="images/github.png" alt="GitHub">
            <img src="images/pycharm.png" alt="PyCharm">
            <img src="images/google_colab.png" alt="Google Colab">
        </div>

        <h2>Technologies/Frameworks:</h2>
        <div class="skills">
            <img src="images/react_native.png" alt="React Native">
            <img src="images/flask.png" alt="Flask">
            <img src="images/firebase.png" alt="Firebase">
            <img src="images/django.png" alt="Django">
        </div>

        <h2>Cloud:</h2>
        <div class="skills">
            <img src="images/azure.png" alt="Microsoft Azure">
        </div>
    </div>
</body>
</html>

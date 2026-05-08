<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eldad Haber - Personal Website</title>
    <style>
        /* Base Styles */
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Roboto", "Segoe UI", Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #fcfcfc;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            display: flex;
            flex-wrap: wrap;
            padding: 40px 20px;
        }

        /* Sidebar Styling */
        .sidebar {
            flex: 1;
            min-width: 250px;
            padding-right: 40px;
            text-align: center;
        }

        .profile-pic {
            width: 200px;
            height: 200px;
            border-radius: 50%; /* Makes it circular like the original */
            object-fit: cover;
            border: 1px solid #ddd;
            margin-bottom: 20px;
        }

        .sidebar h2 { margin-bottom: 5px; }
        .sidebar p { color: #666; margin-top: 0; }

        .social-links {
            list-style: none;
            padding: 0;
            text-align: left;
            border-top: 1px solid #eee;
            padding-top: 20px;
        }

        .social-links li { margin-bottom: 10px; font-size: 0.9em; }
        .social-links a { color: #4979ff; text-decoration: none; }

        /* Main Content Styling */
        .main-content {
            flex: 3;
            min-width: 350px;
        }

        nav {
            margin-bottom: 30px;
            border-bottom: 1px solid #eee;
            padding-bottom: 10px;
        }

        nav a {
            margin-right: 20px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }

        h1 { border-bottom: 1px solid #eee; padding-bottom: 10px; }

        footer {
            margin-top: 50px;
            font-size: 0.8em;
            color: #999;
            border-top: 1px solid #eee;
            padding-top: 20px;
            width: 100%;
        }

        /* Mobile Responsive */
        @media (max-width: 768px) {
            .container { flex-direction: column; }
            .sidebar { padding-right: 0; margin-bottom: 40px; }
        }
    </style>
</head>
<body>

<div class="container">
    <aside class="sidebar">
        <img src="https://via.placeholder.com/200" alt="Profile Picture" class="profile-pic">
        
        <h2>Your Name</h2> <p>Title / Position</p> <ul class="social-links">
            <li>📧 <a href="mailto:eldadHaber@gmail.com">Email</a></li>
            <li>🐦 <a href="#">Twitter</a></li>
            <li>🎓 <a href="#">Google Scholar</a></li>
        </ul>
    </aside>

    <main class="main-content">
        <nav>
            <a href="#">About</a>
            <a href="#">Publications</a>
            <a href="#">Teaching</a>
            <a href="#">Gallery</a>
        </nav>

        <h1>About Me</h1>
        <p>
            Welcome to my website! I am a professor at the University of British Columbia. 
            My work focuses on Scientific ML.
        </p>
        
        <p>
            
        </p>

        <h2>Research Interests</h2>
        <ul>
            <li>Numerical Deep Learning</li>
            <li>Inverse Problems</li>
            <li>Numerical ODEs and PDEs</li>
            <li>Applications</li>
        </ul>

        <footer>
            © Eldad Haber.
        </footer>
    </main>
</div>

</body>
</html>

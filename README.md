<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prakash Rajendran - Professional Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }

        /* Header */
        header {
            background-color: #003366;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 36px;
        }

        header p {
            margin: 5px 0 0;
            font-size: 18px;
        }

        /* Main Layout */
        .container {
            display: flex;
            flex-wrap: wrap;
            min-height: 100vh;
        }

        .sidebar {
            background-color: #f4f4f9;
            width: 30%;
            padding: 20px;
            box-sizing: border-box;
            border-right: 3px solid #003366;
        }

        .content {
            width: 70%;
            padding: 20px;
            box-sizing: border-box;
        }

        /* Sidebar Styling */
        .sidebar h2 {
            color: #003366;
        }

        .sidebar .icons a {
            text-decoration: none;
            color: #003366;
            margin: 0 10px;
            font-size: 24px;
        }

        .sidebar .icons a:hover {
            color: #1da1f2; /* LinkedIn blue */
        }

        .sidebar .button {
            display: inline-block;
            padding: 10px 20px;
            margin-top: 15px;
            background-color: #1da1f2;
            color: white;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
        }

        .sidebar .button:hover {
            background-color: #0073b1; /* LinkedIn darker blue */
        }

        /* Content Section */
        .content h2 {
            color: #003366;
            margin-bottom: 10px;
        }

        .content p {
            font-size: 16px;
            line-height: 1.6;
        }

        .content ul {
            list-style-type: none;
            padding: 0;
        }

        .content ul li {
            margin-bottom: 10px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .sidebar {
                width: 100%;
                border-right: none;
                border-bottom: 3px solid #003366;
            }

            .content {
                width: 100%;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Prakash Rajendran</h1>
        <p>Software Engineer | Web and Backend Specialist</p>
    </header>

    <!-- Main Content -->
    <div class="container">
        <!-- Sidebar -->
        <div class="sidebar">
            <h2>Contact & Links</h2>
            <div class="icons">
                <a href="https://www.linkedin.com/in/theprakashrajendran" target="_blank" title="LinkedIn">
                    <i class="fab fa-linkedin"></i>
                </a>
                <a href="https://github.com/theprakashrajendran" target="_blank" title="GitHub">
                    <i class="fab fa-github"></i>
                </a>
                <a href="mailto:theprakashrajendran@gmail.com" title="Email">
                    <i class="fas fa-envelope"></i>
                </a>
            </div>
            <a href="prakashrajendranresume.pdf" class="button" download>Download Resume</a>
        </div>

        <!-- Content Section -->
        <div class="content">
            <h2>Professional Experience</h2>
            <ul>
                <li><strong>Company 1:</strong> NN Life Japan (May 2022 - Present) - Automation Cloud Engineer</li>
                <li><strong>Company 2:</strong> TechMahindra (May 2016 - Mar 2022) - Technical Lead</li>
                <li><strong>Company 3:</strong> Hexacorp (Jan 2014 - Apr 2016) - Senior Software Engineer</li>
                <li><strong>Company 4:</strong> B & A Digitactical (Jan 2012 - Jan 2014) - Software Engineer</li>
                <li><strong>Company 5:</strong> BEL (Dec 2010 - Dec 2011) - Trainee</li>
            </ul>
        </div>
    </div>
</body>
</html>

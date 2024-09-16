<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adam Agbaria's GitHub</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            min-height: 100vh;
        }
        header {
            text-align: center;
            background-color: #1f1f1f;
            color: white;
            padding: 20px;
            width: 100%;
        }
        header h1 {
            margin: 0;
        }
        .content {
            max-width: 800px;
            text-align: center;
            padding: 20px;
        }
        .btn {
            display: inline-block;
            margin: 10px;
            padding: 12px 24px;
            background-color: #007acc;
            color: white;
            text-decoration: none;
            border-radius: 6px;
        }
        .btn:hover {
            background-color: #005f99;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .project {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            text-align: left;
        }
        .project h3 {
            margin-top: 0;
        }
        footer {
            margin-top: 20px;
            background-color: #1f1f1f;
            color: white;
            width: 100%;
            padding: 20px;
            text-align: center;
        }
        .social-links a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
        }
        .social-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Adam Agbaria's GitHub</h1>
        <p>Software Engineer | Android Developer | Machine Learning Enthusiast</p>
    </header>

    <div class="content">
        <h2>Welcome to My GitHub!</h2>
        <p>I'm Adam, a passionate developer specializing in Android apps, machine learning, and full-stack development. Here you'll find my projects, open-source contributions, and technical experiments.</p>

        <a class="btn" href="https://github.com/Adam-Agbaria">Check My GitHub Repositories</a>
        <a class="btn" href="mailto:agbariaadam@yahoo.com">Contact Me</a>

        <section class="projects">
            <div class="project">
                <h3>🛠️ Project: TripMaster</h3>
                <p>A travel superapp that includes flight and hotel search, vacation packages, and much more!</p>
                <a class="btn" href="https://github.com/Adam-Agbaria/Tripmaster" target="_blank">View on GitHub</a>
            </div>
            <div class="project">
                <h3>📈 Serverless Deployment Pipeline</h3>
                <p>A serverless deployment pipeline using AWS Lambda functions, DynamoDB, CodePipeline, and other AWS services to automate deployments.</p>
                <a class="btn" href="https://github.com/Adam-Agbaria/aws-serverless-deployment-pipeline" target="_blank">View on GitHub</a>
            </div>
            <div class="project">
                <h3>📱 Permissions Manager</h3>
                <p>An Android library to dynamically handle app permissions and updates in real-time.</p>
                <a class="btn" href="https://github.com/Adam-Agbaria/Permission-Manager-Library" target="_blank">View on GitHub</a>
            </div>
        </section>
    </div>

    <footer>
        <p>Follow Me On</p>
        <div class="social-links">
            <a href="https://linkedin.com/in/adam-agbaria-8a8310219" target="_blank">LinkedIn</a> |
            <a href="https://github.com/Adam-Agbaria" target="_blank">GitHub</a> |
            <a href="mailto:agbariaadam@yahoo.com">Email</a>
        </div>
    </footer>
</body>
</html>

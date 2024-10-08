
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prajval's Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* styles.css */

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f4f4f4;
            width: 100%;
        }

        header, nav, section, footer {
            width: 100%;
            max-width: 100%;
            box-sizing: border-box;
        }

        header {
            background: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        nav ul {
            list-style: none;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin: 0 10px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 20px;
            margin: 0 auto;
            box-sizing: border-box;
        }

        .project {
            margin-bottom: 20px;
        }

        .project h3 {
            margin: 0;
        }

        .project ul {
            list-style: none;
            padding: 0;
        }

        .project ul li {
            margin: 5px 0;
        }

        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
            position: relative;
        }

        ul {
            padding: 0;
            margin: 0;
            list-style: none;
        }

        ul li {
            margin-bottom: 10px;
        }

        ul li a {
            text-decoration: none;
            color: inherit;
            display: flex;
            align-items: center;
        }

        ul li a i {
            margin-right: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Prajval's Portfolio</h1>
        <a href="mailto:prajval.yadavannavar@example.com" target="_blank">
            <i class="fas fa-envelope"></i> Email
        </a>
        <p>Analytics Portfolio</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm Prajval Yadavannavar, a passionate data analyst with expertise in analyzing and visualizing data to uncover insights. I have a strong foundation in tools like Python, SQL, and Power BI, and I'm committed to using data to drive strategic decisions.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>1. Sales Data Analysis</h3>
            <p>Analyzed retail sales data to identify trends and areas for improvement.</p>
            <ul>
                <li><strong>Tools Used:</strong> Python, Pandas, Matplotlib</li>
                <li><strong>Key Insights:</strong> Identified regional sales patterns and recommended marketing strategies.</li>
                <li><a href="#">View Project</a></li>
            </ul>
        </div>
        <div class="project">
            <h3>2. Customer Segmentation Using K-Means Clustering</h3>
            <p>Segmented customers for targeted marketing using K-Means clustering.</p>
            <ul>
                <li><strong>Tools Used:</strong> Python, Scikit-learn, Seaborn</li>
                <li><strong>Key Insights:</strong> Defined customer segments to optimize marketing efforts.</li>
                <li><a href="#">View Project</a></li>
            </ul>
        </div>
        <div class="project">
            <h3>3. Financial Data Dashboard</h3>
            <p>Created an interactive Power BI dashboard for financial performance analysis.</p>
            <ul>
                <li><strong>Tools Used:</strong> Power BI, SQL</li>
                <li><strong>Key Insights:</strong> Visualized revenue, expenses, and profit trends.</li>
                <li><a href="#">View Project</a></li>
            </ul>
        </div>
        <div class="project">
            <h3>4. Employee Performance Analysis</h3>
            <p>Analyzed employee performance data to improve training programs.</p>
            <ul>
                <li><strong>Tools Used:</strong> Excel, Python, Matplotlib</li>
                <li><strong>Key Insights:</strong> Correlated training hours with performance improvements.</li>
                <li><a href="#">View Project</a></li>
            </ul>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>If you'd like to get in touch, feel free to reach out to me through the following:</p>
        <ul>
            <li>
                <a href="mailto:prajval.yadavannavar@example.com" target="_blank">
                    <i class="fas fa-envelope"></i> Email
                </a>
            </li>
            <li>
                <a href="https://linkedin.com/in/prajval-yadavannavar" target="_blank">
                    <i class="fab fa-linkedin"></i> LinkedIn
                </a>
            </li>
            <li>
                <a href="https://github.com/prajvalyadavannavar" target="_blank">
                    <i class="fab fa-github"></i> GitHub
                </a>
            </li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2024 Prajval Yadavannavar. All rights reserved.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Education Mathematics | Your Learning Journey Begins Here</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Open+Sans:wght@400&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #007bff;
            --secondary-color: #0056b3;
            --text-color: #f8f9fa;
            --overlay-color: rgba(0, 0, 0, 0.6); /* Darker overlay for text contrast */
        }

        body {
            margin: 0;
            font-family: 'Open Sans', sans-serif;
            color: var(--text-color);
            overflow: hidden; /* Prevent scrollbars if content overflows */
        }

        .cover-page {
            position: relative;
            width: 100vw;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: url('https://via.placeholder.com/1920x1080/007bff/FFFFFF?text=Mathematics+Background') no-repeat center center/cover; /* Placeholder image */
            /* You can replace the above URL with your own image, e.g.: */
            /* background: url('your-math-background-image.jpg') no-repeat center center/cover; */
        }

        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: var(--overlay-color);
            z-index: 1; /* Ensure overlay is above background but below content */
        }

        .content {
            position: relative;
            z-index: 2; /* Ensure content is above the overlay */
            max-width: 900px;
            padding: 20px;
        }

        h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 3.5em; /* Larger for impact */
            margin-bottom: 0.2em;
            color: var(--text-color);
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }

        p {
            font-size: 1.3em;
            margin-bottom: 1.5em;
            line-height: 1.5;
            color: var(--text-color);
            text-shadow: 1px 1px 3px rgba(0,0,0,0.4);
        }

        .button {
            display: inline-block;
            background-color: var(--primary-color);
            color: white;
            padding: 15px 30px;
            border-radius: 5px;
            text-decoration: none;
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
            font-size: 1.1em;
            transition: background-color 0.3s ease, transform 0.2s ease;
            box-shadow: 0 4px 6px rgba(0,0,0,0.3);
        }

        .button:hover {
            background-color: var(--secondary-color);
            transform: translateY(-2px); /* Slight lift effect */
        }

        /* Responsive adjustments */
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5em;
            }
            p {
                font-size: 1em;
            }
            .button {
                padding: 12px 25px;
                font-size: 1em;
            }
        }

        @media (max-width: 480px) {
            h1 {
                font-size: 2em;
            }
            p {
                font-size: 0.9em;
            }
            .button {
                padding: 10px 20px;
                font-size: 0.9em;
            }
        }
    </style>
</head>
<body>
    <div class="cover-page">
        <div class="overlay"></div>
        <div class="content">
            <h1>E-Education Mathematics</h1>
            <p>Unlock the world of numbers and logic. Your comprehensive guide to mastering mathematical concepts from basic to advanced levels.</p>
            <a href="main-content.html" class="button">Start Learning Now!</a>
        </div>
    </div>
</body>
</html>

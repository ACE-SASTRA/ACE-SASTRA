<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ACE SASTRA</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
            margin: 0;
            padding: 0;
        }

        h1 {
            text-align: center;
            background: linear-gradient(90deg, #6a11cb, #2575fc);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin: 20px 0;
        }

        h2 {
            text-align: center;
            color: #2575fc;
            font-size: 1.5rem;
            transition: transform 0.3s;
        }

        h2:hover {
            transform: scale(1.1);
            color: #6a11cb;
        }

        .cluster {
            display: flex;
            align-items: center;
            flex-direction: column;
            margin: 20px 0;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .cluster img {
            width: 300px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .cluster img:hover {
            transform: scale(1.1);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
        }

        .cluster p {
            margin-top: 10px;
            font-style: italic;
            color: #666;
        }

        footer {
            text-align: center;
            margin-top: 50px;
            padding: 10px 0;
            background-color: #2575fc;
            color: white;
            font-size: 0.9rem;
            letter-spacing: 1px;
        }

        footer:hover {
            background-color: #6a11cb;
            transition: background-color 0.3s;
        }
    </style>
</head>
<body>
    <h1>Welcome to ACE-SASTRA</h1>
    <p style="text-align: center;">ACE aims to promote excellence in computing education and research by organizing exciting events, hackathons, webinars, and workshops.</p>

    <div class="cluster">
        <h2>Web Development Cluster</h2>
        <img src="https://github.com/user-attachments/assets/b4bb65bc-098a-4093-86d2-baf87fdd56f8" alt="Web Development">
        <p>Bringing innovative websites to life with cutting-edge technologies.</p>
    </div>

    <div class="cluster">
        <h2>Video Editing Cluster</h2>
        <img src="https://github.com/user-attachments/assets/1fdd1b42-04c5-4bfd-86c1-3f28594ee9f0" alt="Video Editing">
        <p>Transforming raw footage into engaging visual masterpieces.</p>
    </div>

    <div class="cluster">
        <h2>Operations and Control (OpCon) Cluster</h2>
        <img src="https://github.com/user-attachments/assets/76706c8c-c00d-454c-b76e-997a3d4fe917" alt="OpCon">
        <p>Managing and coordinating with precision for seamless execution.</p>
    </div>

    <!-- Add additional clusters similarly -->

    <footer>More News to Come. Stay Tuned!</footer>
</body>
</html>

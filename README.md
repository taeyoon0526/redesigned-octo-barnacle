taeyoon0526.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram Theme</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #fafafa;
        }

        /* Header */
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
            background-color: #ffffff;
            border-bottom: 1px solid #dbdbdb;
            position: sticky;
            top: 0;
            z-index: 10;
        }

        .header img {
            height: 40px;
        }

        .header input {
            border: 1px solid #dbdbdb;
            border-radius: 5px;
            padding: 5px 10px;
            width: 200px;
        }

        /* Feed */
        .feed {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }

        .post {
            background-color: #ffffff;
            border: 1px solid #dbdbdb;
            border-radius: 5px;
            margin-bottom: 20px;
            width: 100%;
            max-width: 500px;
        }

        .post img {
            width: 100%;
            border-bottom: 1px solid #dbdbdb;
        }

        .post .info {
            padding: 10px;
        }

        .post .info h4 {
            margin: 0;
        }

        .post .info p {
            margin: 5px 0 0 0;
            color: #8e8e8e;
        }

        /* Footer */
        .footer {
            text-align: center;
            padding: 20px;
            background-color: #ffffff;
            border-top: 1px solid #dbdbdb;
            margin-top: 20px;
        }

        .footer a {
            color: #00376b;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <div class="header">
        <img src="https://via.placeholder.com/100x40?text=Logo" alt="Logo">
        <input type="text" placeholder="Search">
        <img src="https://via.placeholder.com/40" alt="Profile Icon" style="border-radius: 50%;">
    </div>

    <!-- Feed -->
    <div class="feed">
        <div class="post">
            <img src="https://via.placeholder.com/500x300?text=Post+Image" alt="Post Image">
            <div class="info">
                <h4>@username</h4>
                <p>Caption goes here...</p>
            </div>
        </div>
        <div class="post">
            <img src="https://via.placeholder.com/500x300?text=Another+Post" alt="Post Image">
            <div class="info">
                <h4>@anotheruser</h4>
                <p>Another caption here...</p>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <div class="footer">
        <p>© 2025 Instagram Theme. <a href="#">Privacy</a> • <a href="#">Terms</a></p>
    </div>
</body>
</html>

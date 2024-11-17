<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proceed Button Interface</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f4f4;
        }
        .container {
            text-align: center;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 10px;
            background: #fff;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        h1 {
            font-size: 24px;
            margin-bottom: 20px;
            color: pink; /* Ensures the text is pink */
            font-weight: bold; /* Ensures the text is bold */
        }
        img {
            max-width: 60%;
            height: auto;
            margin-bottom: 20px;
            border-radius: 10px; /* Optional: adds rounded corners to the image */
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            color: #fff;
            background-color: #007bff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Make sure the 'src' path matches the actual file location -->
        <img src="https://scontent.fmnl13-3.fna.fbcdn.net/v/t39.30808-6/454633457_1933920557050209_7807125101872990053_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=6ee11a&_nc_eui2=AeEeiNtUJ4xQkcVVAGcvbayWtvg-hxAx20S2-D6HEDHbROBfEnUcFHgampvqFnZklFLNjF2xAQGeSIN1PtNKe82q&_nc_ohc=yUFuj3KMlusQ7kNvgGXH9bw&_nc_zt=23&_nc_ht=scontent.fmnl13-3.fna&_nc_gid=AYWPRmRkq822oKmhrqZeKmd&oh=00_AYC7uH3_UEHcME0ys8kzQ_trMLvZUuf1H-ilF3MrghbQAA&oe=673FDBAE" alt="The del Mundos">
        <h1>The Del Mundos</h1>
        <button onclick="proceed()">Proceed</button>
    </div>

    <script>
        function proceed() {
            // Redirect to the next page
            window.location.href = "nextpage.html"; // Change "nextpage.html" to the next page file name
        }
    </script>
</body>
</html>


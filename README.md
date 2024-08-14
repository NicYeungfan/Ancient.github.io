# Ancient.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4e8c1; /* Ancient parchment-like color */
            color: #333;
            margin: 0;
            padding: 20px;
        }
        h1 {
            color: #8b5a2b; /* Antique brown color for heading */
        }
        .image-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: space-between;
        }
        .image-container img {
            width: calc(33.333% - 10px); /* Each image takes up 1/3 of the row */
            height: auto;
            border: 1px solid #ddd;
            border-radius: 4px;
            padding: 5px;
            background-color: white;
            object-fit: cover; /* Ensures proper aspect ratio */
            aspect-ratio: 4 / 3; /* Adjusts the ratio to a common 4:3 ratio */
        }
    </style>
</head>
<body>
    <h1>Image Gallery</h1>

    <div class="image-container">
        <img src="H1.jpg" alt="Image 1" />
        <img src="H23.jpg" alt="Image 2" />
        <img src="H3.jpg" alt="Image 3" />
        <img src="H4.jpg" alt="Image 4" />
        <img src="H5.jpg" alt="Image 5" />
        <img src="H6.jpg" alt="Image 6" />
        <img src="H7.jpg" alt="Image 7" />
        <img src="Han2.jpg" alt="Image 8" />
    </div>
</body>
</html>


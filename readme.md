# Animated Earth

To create an animated Earth, you can use HTML and CSS. Below is an example of how you can achieve this:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animated Earth</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #000;
            margin: 0;
        }
        .earth {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            background: url('https://example.com/earth-texture.jpg') no-repeat center/cover;
            animation: rotate 10s linear infinite;
        }
        @keyframes rotate {
            from {
                transform: rotate(0deg);
            }
            to {
                transform: rotate(360deg);
            }
        }
    </style>
</head>
<body>
    <div class="earth"></div>
</body>
</html>
```

Replace `'https://example.com/earth-texture.jpg'` with the URL of your Earth texture image.

git clone https://github.com/dhegehe33/RTX-Discord-Server-Website.githttps://github.com/username/username.github.io.git
cd username.github.io
# أنشئ ملف index.html وضع فيه الكود التالي:
echo "<!DOCTYPE html>
<html lang=\"en\">
<head>
    <meta charset=\"UTF-8\">
    <meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\">
    <title>My GitHub Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
        }
        h1 {
            color: #333;
        }
    </style>
</head>
<body>
    <h1>Welcome to My GitHub Page</h1>
    <p>This is a simple website hosted with GitHub Pages.</p>
</body>
</html>" > index.html
git add .
git commit -m "Initial commit"
git push origin main

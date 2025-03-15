<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fullscreen Iframe</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            overflow: hidden; /* Menghindari scroll */
        }
        iframe {
            height: 100vh;
            width: 100vw;
            border: 0;
        }
    </style>
</head>
<body>
    <iframe
        allow="camera; microphone; display-capture; fullscreen; clipboard-read; clipboard-write; web-share; autoplay"
        src="https://sfu.mirotalk.com/newroom"
    ></iframe>
</body>
</html>

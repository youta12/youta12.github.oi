<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HALLO SAYANG</title>
    <style>
        #photo {
            display: none;
        }
    </style>
    <script>
        function showPhoto() {
            document.getElementById('photo').style.display = 'block';
        }
    </script>
</head>
<body>
    <h1><a href="#" onclick="showPhoto()">pencet</a></h1>
    <img id="photo" src="untukKamu.png" alt="untuk kamu" width="500">
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    .c1{
        background: blueviolet;
        width: 300px;
        border: 5px solid green;
        padding: 5px;
        margin: 5px;
    }
    .bgchange {
        background: orange;
    }
</style>

<body>
    <h1 id="demo"></h1>
    <div class="c1">
        <h1>this is Heading script</h1>
    </div>
    <div class="c1">
        <p>paragrapg</p>
    </div>

    <script>
        document.getElementById("demo").innerHTML = "welcome to javascript"
    </script>

    <script src="domjs.js"></script>
</body>
</html>

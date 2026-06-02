<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ToolBucket - Free Online Tools</title>

<style>
body{
    margin:0;
    font-family: Arial, sans-serif;
    background:#f5f7fb;
}

header{
    background: linear-gradient(135deg,#4a90e2,#6c5ce7);
    color:white;
    padding:30px 20px;
    text-align:center;
}

header h1{
    margin:0;
    font-size:40px;
}

header p{
    margin-top:10px;
    opacity:0.9;
}

.container{
    max-width:1000px;
    margin:auto;
    padding:20px;
}

.tools{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
    margin-top:20px;
}

.card{
    background:white;
    padding:25px;
    border-radius:15px;
    text-align:center;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-5px);
}

.card a{
    text-decoration:none;
    color:#333;
    font-weight:bold;
    font-size:18px;
}

footer{
    text-align:center;
    padding:15px;
    background:#222;
    color:white;
    margin-top:30px;
}
</style>

</head>

<body>

<header>
    <h1>ToolBucket</h1>
    <p>All Free Online Tools in One Place</p>
</header>

<div class="container">

    <h2>Popular Tools</h2>

    <div class="tools">

        <div class="card">
            <a href="age-calculator.html">Age Calculator</a>
        </div>

        <div class="card">
            <a href="#">Percentage Calculator</a>
        </div>

        <div class="card">
            <a href="#">BMI Calculator</a>
        </div>

        <div class="card">
            <a href="#">Loan Calculator</a>
        </div>

        <div class="card">
            <a href="#">Unit Converter</a>
        </div>

    </div>

</div>

<footer>
    © 2026 ToolBucket | Made with ❤️
</footer>

</body>
</html>

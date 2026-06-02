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
    background: linear-gradient(135deg,#0f2027,#203a43,#2c5364);
    color:white;
}

/* HEADER */
header{
    text-align:center;
    padding:40px 20px;
}

header h1{
    font-size:45px;
    margin:0;
    background: linear-gradient(90deg,#ff9a9e,#fad0c4,#fbc2eb);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
}

header p{
    opacity:0.9;
    margin-top:10px;
}

/* CONTAINER */
.container{
    max-width:1000px;
    margin:auto;
    padding:20px;
}

/* TOOL CARDS */
.tools{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.card{
    background: rgba(255,255,255,0.1);
    backdrop-filter: blur(10px);
    padding:25px;
    border-radius:15px;
    text-align:center;
    border:1px solid rgba(255,255,255,0.2);
    transition:0.3s;
}

.card:hover{
    transform: scale(1.05);
    background: rgba(255,255,255,0.2);
}

.card a{
    text-decoration:none;
    color:white;
    font-weight:bold;
    font-size:18px;
}

/* FOOTER */
footer{
    text-align:center;
    padding:15px;
    margin-top:30px;
    background: rgba(0,0,0,0.4);
}
</style>

</head>

<body>

<header>
    <h1>ToolBucket</h1>
    <p>One Place for All Free Online Tools</p>
</header>

<div class="container">

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
    © 2026 ToolBucket | Built for Free Tools Lovers
</footer>

</body>
</html>

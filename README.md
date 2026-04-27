# Trigonometrijosuzdaviniai
Šiame puslapyje galėsite pakartoti pagrindines trigonometrijos sąvokas ir įgūdžius. Trigonometrija nagrinėja kampų ir trikampių kraštinių tarpusavio ryšiu
<!DOCTYPE html>
<html lang="lt">
<head>
<meta charset="UTF-8">
<title>Trigonometrijos kartojimas</title>

<style>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f6f8;
    margin: 20px;
    line-height: 1.6;
}

h1 {
    text-align: center;
}

.box {
    background: white;
    padding: 20px;
    margin-bottom: 30px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

ol li {
    margin-bottom: 12px;
    font-size: 16px;
}

.answers {
    display: none;
    margin-top: 40px;
}

.answers p {
    margin-bottom: 10px;
}

button {
    padding: 10px 20px;
    font-size: 16px;
    border: none;
    border-radius: 8px;
    background-color: #4CAF50;
    color: white;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}
</style>

<script>
function toggleAnswers() {
    var x = document.getElementById("answers");
    if (x.style.display === "none") {
        x.style.display = "block";
    } else {
        x.style.display = "none";
    }
}
</script>

</head>

<body>

<h1>Trigonometrijos kartojimas</h1>

<div class="box">
    <h2>Pagrindai</h2>
    <p><b>sin(α)</b> = priešpriešinė / įžambinė</p>
    <p><b>cos(α)</b> = prigludusioji / įžambinė</p>
    <p><b>tan(α)</b> = priešpriešinė / prigludusioji</p>
</div>

<div class="box">
    <h2>Uždaviniai (klausimai)</h2>
    <ol>
        <li>Rask sin(30°)</li>
        <li>Rask cos(60°)</li>
        <li>Rask tan(45°)</li>
        <li>Jei priešpriešinė = 3, įžambinė = 5, rask sin(α)</li>
        <li>Jei prigludusioji = 4, įžambinė = 5, rask cos(α)</li>
        <li>Rask kampą, jei sin(α) = 0.5</li>
        <li>Rask kampą, jei cos(α) = 0.5</li>
        <li>Rask kampą, jei tan(α) = 1</li>
        <li>Rask sin²(α) + cos²(α)</li>
        <li>Jei tan(α) = 2, ką tai reiškia santykiu?</li>
    </ol>
</div>

<div style="text-align:center;">
    <button onclick="toggleAnswers()">Rodyti / Slėpti atsakymus</button>
</div>

<div class="box answers" id="answers">
    <h2>Atsakymai (apačioje)</h2>
    <p>1) 0.5</p>
    <p>2) 0.5</p>
    <p>3) 1</p>
    <p>4) 3/5</p>
    <p>5) 4/5</p>
    <p>6) 30°</p>
    <p>7) 60°</p>
    <p>8) 45°</p>
    <p>9) 1</p>
    <p>10) priešpriešinė = 2 × prigludusioji</p>
</div>

</body>
</html>

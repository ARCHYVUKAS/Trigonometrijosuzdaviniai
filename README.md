# Trigonometrijosuzdaviniai
Šiame puslapyje galėsite pakartoti pagrindines trigonometrijos sąvokas ir įgūdžius. Trigonometrija nagrinėja kampų ir trikampių kraštinių tarpusavio ryšiu
<!DOCTYPE html>
<html lang="lt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trigonometrija: Sinusas, Kosinusas, Tangentas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            background: #f9f9f9;
            color: #333;
        }
        h1, h2, h3 { color: #2c3e50; }
        .section {
            background: white;
            padding: 25px;
            margin-bottom: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .formula {
            font-size: 1.3em;
            background: #f0f0f0;
            padding: 15px;
            border-left: 5px solid #3498db;
            margin: 15px 0;
        }
        .uzduotis {
            background: #f8f9fa;
            padding: 18px;
            margin: 15px 0;
            border-left: 6px solid #e74c3c;
            border-radius: 5px;
        }
        .atsakymas {
            background: #e8f5e9;
            padding: 12px 18px;
            margin-top: 10px;
            border-left: 6px solid #27ae60;
            display: none;
        }
        button {
            background: #3498db;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }
        button:hover { background: #2980b9; }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: center;
        }
        th { background: #3498db; color: white; }
    </style>
</head>
<body>

    <h1>📐 Trigonometrija: Sinusas, Kosinusas ir Tangentas</h1>

    <div class="section">
        <h2>Pagrindinės savybės</h2>
        
        <h3>1. Sinusas (sin)</h3>
        <div class="formula">
            sin(θ) = priešingos kraštinės / įžambinės (stačiakampiame trikampyje)<br>
            sin(0) = 0  sin(30°) = 1/2  sin(45°) = √2/2  sin(60°) = √3/2  sin(90°) = 1
        </div>
        <p><strong>Savybės:</strong></p>
        <ul>
            <li>sin(-θ) = -sin(θ)</li>
            <li>sin(180° - θ) = sin(θ)</li>
            <li>sin(180° + θ) = -sin(θ)</li>
            <li>sin(360° - θ) = -sin(θ)</li>
            <li>sin(θ + 360°) = sin(θ)  (periodiškumas 360°)</li>
        </ul>

        <h3>2. Kosinusas (cos)</h3>
        <div class="formula">
            cos(θ) = gretimos kraštinės / įžambinės<br>
            cos(0) = 1  cos(30°) = √3/2  cos(45°) = √2/2  cos(60°) = 1/2  cos(90°) = 0
        </div>
        <p><strong>Savybės:</strong></p>
        <ul>
            <li>cos(-θ) = cos(θ)</li>
            <li>cos(180° - θ) = -cos(θ)</li>
            <li>cos(180° + θ) = -cos(θ)</li>
            <li>cos(360° - θ) = cos(θ)</li>

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
            <li>cos(θ + 360°) = cos(θ)</li>
        </ul>

        <h3>3. Tangentas (tan)</h3>
        <div class="formula">
            tan(θ) = sin(θ) / cos(θ) = priešingos kraštinės / gretimos kraštinės<br>
            tan(0) = 0  tan(30°) = 1/√3  tan(45°) = 1  tan(60°) = √3
        </div>
        <p><strong>Savybės:</strong></p>
        <ul>
            <li>tan(-θ) = -tan(θ)</li>
            <li>tan(180° - θ) = -tan(θ)</li>
            <li>tan(180° + θ) = tan(θ)</li>
            <li>tan(θ + 180°) = tan(θ)  (periodiškumas 180°)</li>
            <li>tan(θ) nėra apibrėžtas, kai cos(θ) = 0 (90°, 270° ir t.t.)</li>
        </ul>

        <h3>Pagrindinė tapatybė (Pitagoro tapatybė)</h3>
        <div class="formula">
            sin²(θ) + cos²(θ) = 1
        </div>
    </div>

    <div class="section">
        <h2>20 Trigonometrijos uždavinių su atsakymais</h2>
        
        <h3>1–10 uždaviniai (paprasti)</h3>
        
        <div class="uzduotis">
            <strong>1.</strong> Rask sin(30°), cos(30°), tan(30°).<br>
            <button onclick="rodytiAtsakyma(1)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats1">
                sin(30°) = 1/2, cos(30°) = √3/2, tan(30°) = 1/√3 ≈ 0.577
            </div>
        </div>

        <div class="uzduotis">
            <strong>2.</strong> Rask sin(60°), cos(60°), tan(60°).<br>
            <button onclick="rodytiAtsakyma(2)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats2">
                sin(60°) = √3/2, cos(60°) = 1/2, tan(60°) = √3 ≈ 1.732
            </div>
        </div>

        <div class="uzduotis">
            <strong>3.</strong> Rask sin(45°), cos(45°), tan(45°).<br>
            <button onclick="rodytiAtsakyma(3)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats3">
                sin(45°) = cos(45°) = √2/2 ≈ 0.707, tan(45°) = 1
            </div>
        </div>

        <div class="uzduotis">
            <strong>4.</strong> Rask sin(90°), cos(90°), tan(90°).<br>
            <button onclick="rodytiAtsakyma(4)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats4">
                sin(90°) = 1, cos(90°) = 0, tan(90°) = nenustatytas (begalinis)
            </div>
        </div>

        <div class="uzduotis">
            <strong>5.</strong> Rask sin(0°), cos(0°), tan(0°).<br>
            <button onclick="rodytiAtsakyma(5)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats5">
                sin(0°) = 0, cos(0°) = 1, tan(0°) = 0
            </div>
        </div>

        <div class="uzduotis">
            <strong>6.</strong> Jeigu sin(θ) = 3/5 ir θ yra I ketvirtyje, rask cos(θ) ir tan(θ).<br>
            <button onclick="rodytiAtsakyma(6)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats6">
                cos(θ) = 4/5, tan(θ) = 3/4
            </div>
        </div>

        <div class="uzduotis">
            <strong>7.</strong> Jeigu cos(θ) = 5/13 ir θ yra IV ketvirtyje, rask sin(θ) ir tan(θ).<br>
            <button onclick="rodytiAtsakyma(7)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats7">
                sin(θ) = -12/13, tan(θ) = -12/5
            </div>
        </div>

        <div class="uzduotis">
            <strong>8.</strong> Supaprastink: sin(180° - θ) + sin(180° + θ)<br>
            <button onclick="rodytiAtsakyma(8)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats8">
                sin(180° - θ) + sin(180° + θ) = sin(θ) + (-sin(θ)) = 0
            </div>
        </div>

        <div class="uzduotis">
            <strong>9.</strong> Rask tan(135°)<br>
            <button onclick="rodytiAtsakyma(9)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats9">
                tan(135°) = tan(180° - 45°) = -tan(45°) = -1
            </div>
        </div>

        <div class="uzduotis">
            <strong>10.</strong> Rask sin(210°) ir cos(210°)<br>
            <button onclick="rodytiAtsakyma(10)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats10">
                sin(210°) = -1/2, cos(210°) = -√3/2
            </div>
        </div>

        <h3>11–20 uždaviniai (sudėtingesni)</h3>

        <div class="uzduotis">
            <strong>11.</strong> Išspręsk: sin(θ) = 1/2, rask visus θ intervale [0°, 360°).<br>
            <button onclick="rodytiAtsakyma(11)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats11">
                θ = 30° ir θ = 150°
            </div>
        </div>

        <div class="uzduotis">
            <strong>12.</strong> Jeigu sin(θ) = -√3/2, rask θ intervale [0°, 360°).<br>
            <button onclick="rodytiAtsakyma(12)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats12">
                θ = 210° ir θ = 330°
            </div>
        </div>

        <div class="uzduotis">
            <strong>13.</strong> Rask cos(75°) naudodamas kampų sudėtį (75° = 45° + 30°).<br>
            <button onclick="rodytiAtsakyma(13)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats13">
                cos(75°) = cos(45°+30°) = cos45°cos30° - sin45°sin30° = (√2/2)(√3/2) - (√2/2)(1/2) = (√6 - √2)/4
            </div>
        </div>

        <div class="uzduotis">
            <strong>14.</strong> Įrodyk, kad tan(θ) = sin(θ)/cos(θ) naudojant Pitagoro tapatybę.<br>
            <button onclick="rodytiAtsakyma(14)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats14">
                sin²(θ) + cos²(θ) = 1 → daliname abu narius iš cos²(θ): tan²(θ) + 1 = 1/cos²(θ)
            </div>
        </div>

        <div class="uzduotis">
            <strong>15.</strong> Rask sin(2θ), jeigu sin(θ) = 3/5, o θ yra I ketvirtyje.<br>
            <button onclick="rodytiAtsakyma(15)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats15">
                cos(θ) = 4/5 → sin(2θ) = 2sin(θ)cos(θ) = 2*(3/5)*(4/5) = 24/25
            </div>
        </div>

        <div class="uzduotis">
            <strong>16.</strong> Rask cos(2θ), jeigu cos(θ) = 5/13, o θ yra II ketvirtyje.<br>
            <button onclick="rodytiAtsakyma(16)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats16">
                sin(θ) = 12/13 → cos(2θ) = 2cos²(θ) - 1 = 2*(25/169) - 1 = -119/169
            </div>
        </div>

        <div class="uzduotis">
            <strong>17.</strong> Supaprastink: sin(θ)cos(θ) / (sin²(θ) - cos²(θ))<br>
            <button onclick="rodytiAtsakyma(17)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats17">
                = (1/2)sin(2θ) / (-cos(2θ)) = - (1/2) tan(2θ)
            </div>
        </div>

        <div class="uzduotis">
            <strong>18.</strong> Rask tan(15°) naudodamas kampų atimtį (45° - 30°).<br>
            <button onclick="rodytiAtsakyma(18)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats18">
                tan(15°) = tan(45°-30°) = (1 - 1/√3)/(1 + 1/√3) = 2 - √3
            </div>
        </div>

        <div class="uzduotis">
            <strong>19.</strong> Jeigu sin(θ) + cos(θ) = 1, rask sin(θ)cos(θ).<br>
            <button onclick="rodytiAtsakyma(19)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats19">
                Kvadratuojame: sin² + cos
² + 2sin cos = 1 → 1 + 2sin cos = 1 → sin cos = 0
            </div>
        </div>

        <div class="uzduotis">
            <strong>20.</strong> Rask visas reikšmes intervale [0°, 360°), kai tan(θ) = 1.<br>
            <button onclick="rodytiAtsakyma(20)">Rodyti atsakymą</button>
            <div class="atsakymas" id="ats20">
                θ = 45° ir θ = 225°
            </div>
        </div>
    </div>

    <div class="section">
        <h2>Kaip naudoti šį puslapį GitHub Pages</h2>
        <ol>
            <li>Nukopijuok visą kodą į failą <code>index.html</code></li>
            <li>Sukurk naują repozitoriją GitHub</li>
            <li>Įkelk failą <code>index.html</code></li>
            <li>Eik į Settings → Pages → įjunk GitHub Pages iš main šakos</li>
            <li>Po kelių minučių puslapis bus pasiekiamas adresu: https://tavo-vartotojas.github.io/tavo-repo/</li>
        </ol>
    </div>

    <script>
        function rodytiAtsakyma(nr) {
            const atsakymas = document.getElementById('ats' + nr);
            if (atsakymas.style.display === "block") {
                atsakymas.style.display = "none";
            } else {
                atsakymas.style.display = "block";
            }
        }
    </script>

</body>
</html>

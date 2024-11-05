<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Statistics for Abhiraj Adhikary</title>
<style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 0;
        }
        #stats {
            border: 1px solid #ccc;
            padding: 20px;
            border-radius: 5px;
            max-width: 400px;
        }
        .stat {
            margin-bottom: 15px;
        }
        .stat-label {
            font-weight: bold;
        }
        .progress-bar {
            background-color: #f3f3f3;
            border-radius: 5px;
            overflow: hidden;
            height: 10px;
            margin-top: 5px;
        }
        .progress {
            background-color: #4caf50; /* Green */
            height: 100%;
        }
    </style>
</head>
<body>

<div id="stats" style="display: block;">
    <h2 id="name">Abhiraj Adhikary</h2>
    
<div class="stat">
        <span class="stat-label">Ranking:</span>
        <span id="ranking">1308451</span>
</div>
    
<div class="stat">
        <span class="stat-label">Easy:</span>
        <span id="easy">44 / 832</span>
        <div class="progress-bar">
            <div class="progress" id="easy-progress" style="width: 5.29%;"></div>
        </div>
</div>
    
<div class="stat">
        <span class="stat-label">Medium:</span>
        <span id="medium">23 / 1750</span>
        <div class="progress-bar">
            <div class="progress" id="medium-progress" style="width: 1.31%;"></div>
        </div>
</div>
    
<div class="stat">
        <span class="stat-label">Hard:</span>
        <span id="hard">6 / 761</span>
        <div class="progress-bar">
            <div class="progress" id="hard-progress" style="width: 0.79%;"></div>
        </div>
    </div>
    
<div class="stat">
        <span class="stat-label">Total:</span>
        <span id="total">73 / 3343</span>
    </div>
</div>

</body>
</html>

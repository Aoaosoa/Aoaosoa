<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora de Ratios Financieros</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Calculadora de Ratios Financieros</h1>
    <div class="container">
        <label for="activos">Total Activos:</label>
        <input type="number" id="activos" required>

        <label for="pasivos">Total Pasivos:</label>
        <input type="number" id="pasivos" required>

        <label for="ventas">Ventas Totales:</label>
        <input type="number" id="ventas" required>

        <label for="utilidad">Utilidad Neta:</label>
        <input type="number" id="utilidad" required>

        <label for="capital">Capital Contable:</label>
        <input type="number" id="capital" required>

        <button onclick="calcularRatios()">Calcular Ratios</button>

        <h2>Resultados:</h2>
        <ul id="resultados"></ul>
    </div>
    <script src="script.js"></script>
</body>
</html>

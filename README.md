# Temperature-converter.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Temperature Converter</title>
    <link rel="stylesheet" href="style1.css">
</head>
<body>

    <div class="container">
        <h1>Temperature Converter</h1>

        <!-- Temperature input field -->
        <label for="temperature">Enter Temperature:</label>
        <input type="text" id="temperature" placeholder="Enter temperature">

        <!-- Unit dropdown -->
        <label for="unit">Select Unit:</label>
        <select id="unit">
            <option value="C">Celsius (°C)</option>
            <option value="F">Fahrenheit (°F)</option>
            <option value="K">Kelvin (K)</option>
        </select>

        <!-- Convert button -->
        <button onclick="convertTemperature()">Convert</button>

        <!-- Display result -->
        <div id="result" class="result">
            <!-- Converted temperature will be shown here -->
        </div>
    </div>

    <script src="app.js"></script>
</body>
</html>

# Temperature-converter.css
/* General reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body styling */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f7f7f7;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.container {
    background-color: white;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 400px;
    text-align: center;
}

h1 {
    font-size: 24px;
    margin-bottom: 20px;
}

label {
    font-size: 16px;
    margin: 10px 0;
}

input, select {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
}

button {
    padding: 10px 20px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background-color: #45a049;
}

.result {
    margin-top: 20px;
    font-size: 18px;
    font-weight: bold;
}

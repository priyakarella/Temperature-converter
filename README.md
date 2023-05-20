# Temperature-converter
<!DOCTYPE html>
<html>
<head>
	<title>Temperature Converter</title>
	<link rel="stylesheet" type="text/css" href="convert.css">
</head>
<body>
	<header>
		<h1>Temperature Converter</h1>
	</header>

	<main>
		<form>
			<label for="temp">Enter a temperature:</label>
			<input type="text" id="temp" name="temp" required><br>
                  <br>
			<select id="unit" name="unit">
				<option value="celsius">Celsius</option>
				<option value="fahrenheit">Fahrenheit</option>
			</select><br>
                 <br>
			<input type="button" value="Convert" onclick="convertTemp()">
		</form>

		<div id="result"></div>
	</main>

	<script src="script.js"></script>
</body>
</html>
#CSS
body {
	font-family: Arial, sans-serif;
	margin: 0;
	padding: 0;
}

header {
	background-color: #303F9F;
	color: #FFF;
	padding: 20px 0;
	text-align: center;
}

form {
	display: flex;
	flex-wrap: wrap;
	justify-content: center;
	margin: 20px 0;
}

form label, form select, form input[type="button"] {
	margin: 5px;
}

form input[type="text"] {
	width: 100px;
}

#result {
	font-size: 24px;
	font-weight: bold;
	text-align: center;
	margin-top: 20px;
}

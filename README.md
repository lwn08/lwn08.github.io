<html lang="en">
	<head>
		<script>
			var i = 0
			function increment() {
				i++;
				document.getElementById("score").innerHTML = "You have clicked the button " + i + " times."
			}
		</script>
	</head>
	<body>
		<button onclick="increment()">Click me!</button>
		<p id="score"></p>
	</body>
</html>

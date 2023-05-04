<!DOCTYPE html>
<html>
<head>
	<title>Mi perfil de GitHub</title>
	<style>
		body {
			margin: 0;
			padding: 0;
			font-family: Arial, sans-serif;
		}

		.header {
			background-color: #24292e;
			height: 200px;
			color: white;
			display: flex;
			align-items: center;
			justify-content: center;
			flex-direction: column;
			text-align: center;
		}

		.header h1 {
			font-size: 48px;
			margin: 0;
			padding: 0;
			font-weight: bold;
		}

		.header p {
			font-size: 24px;
			margin: 0;
			padding: 0;
		}

		.profile-picture {
			border-radius: 50%;
			height: 150px;
			width: 150px;
			margin-top: -75px;
			border: 5px solid white;
			background-image: url("https://i.imgur.com/YhPM5g5.jpg");
			background-size: cover;
			background-position: center;
		}

		.content {
			padding: 20px;
		}

		.content h2 {
			font-size: 36px;
			margin-top: 0;
			margin-bottom: 10px;
			font-weight: bold;
		}

		.content p {
			font-size: 24px;
			margin-top: 0;
			margin-bottom: 10px;
		}

		.content ul {
			margin-top: 0;
			margin-bottom: 10px;
			padding-left: 20px;
		}

		.content li {
			font-size: 24px;
			margin-bottom: 5px;
		}
	</style>
</head>
<body>
	<header class="header">
		<div class="profile-picture"></div>
		<h1>Daniel Jiménez</h1>
		<p>Soy desarrollador web Junior FullStack</p>
	</header>
</body>
</html>

<!DOCTYPE html>

<html lang="uz">

<head>

	<title>Lazizbek.uz</title>

	<meta name="viewport" content="width=device-width, initial-scale=1.0">

	<style>

		/* Global stil */

		body, html {

			margin: 0;

			padding: 0;

			font-family: 'Arial', sans-serif;

			background-color: #f4f4f9;

		}



		/* Header */

		header {

			background: linear-gradient(135deg, #1e3c72, #2a5298);

			color: white;

			padding: 20px;

			text-align: center;

			box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);

		}

		header h1 {

			font-size: 36px;

			text-transform: uppercase;

			letter-spacing: 3px;

		}



		/* Navbar */

		nav ul {

			display: flex;

			justify-content: center;

			list-style: none;

			padding: 0;

		}

		nav ul li {

			padding: 15px 30px;

			font-size: 18px;

			transition: 0.3s ease;

		}

		nav ul li:hover {

			background-color: #48a9e6;

			border-radius: 50px;

			transform: translateY(-5px);

		}

		nav ul li a {

			color: white;

			text-decoration: none;

		}



		/* Main Section */

		.main-section {

			display: flex;

			justify-content: space-around;

			flex-wrap: wrap;

			padding: 50px;

			gap: 30px;

		}

		.card {

			background-color: #fff;

			border-radius: 15px;

			overflow: hidden;

			box-shadow: 0 8px 15px rgba(0, 0, 0, 0.1);

			width: 300px;

			text-align: center;

			transition: transform 0.3s ease;

		}

		.card:hover {

			transform: translateY(-10px);

		}

		.card img {

			width: 100%;

			height: 200px;

			object-fit: cover;

		}

		.card p {

			padding: 15px;

			font-size: 20px;

			background-color: #48a9e6;

			color: white;

			margin: 0;

		}



		/* Footer */

		footer {

			background-color: #333;

			color: white;

			padding: 40px 0;

			text-align: center;

		}

		footer h1 {

			font-size: 24px;

			margin-bottom: 20px;

		}

		footer ul {

			display: flex;

			justify-content: center;

			list-style: none;

			padding: 0;

		}

		footer ul li {

			margin: 0 15px;

		}

		footer ul li a {

			color: white;

			text-decoration: none;

			font-size: 18px;

			transition: color 0.3s ease;

		}

		footer ul li a:hover {

			color: #48a9e6;

		}



		/* Modal (Popup) */

		.modal {

			display: none;

			position: fixed;

			z-index: 1;

			left: 0;

			top: 0;

			width: 100%;

			height: 100%;

			background-color: rgba(0, 0, 0, 0.4);

			padding-top: 60px;

		}

		.modal-content {

			background-color: white;

			margin: 5% auto;

			padding: 20px;

			width: 80%;

			max-width: 500px;

			border-radius: 10px;

			box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);

		}

		.close {

			color: #aaa;

			float: right;

			font-size: 28px;

			font-weight: bold;

		}

		.close:hover, .close:focus {

			color: black;

			text-decoration: none;

			cursor: pointer;

		}



		/* Media Queries for Responsiveness */

		@media (max-width: 768px) {

			.main-section {

				flex-direction: column;

				align-items: center;

			}

			.card {

				width: 80%;

				max-width: 350px;

			}

		}

	</style>

</head>

<body>



	<header>

		<h1>Lazizbek.Uz</h1>

		<nav>

			<ul>

				<li><a href="javascript:void(0);" id="login-link">Kirish</a></li>

				<li><a href="javascript:void(0);" id="news-link">Yangilik</a></li>

				<li><a href="javascript:void(0);" id="about-link">Ma'lumot</a></li>

				<li><a href="javascript:void(0);" id="contact-link">Bog'lanish</a></li>

			</ul>

		</nav>

	</header>



	<div class="main-section">

		<div class="card">

			<img src="img131.jpg" alt="Pagani Imola">

			<p>Pagani Imola</p>

		</div>

		<div class="card">

			<img src="img131.jpg" alt="Pagani Imola">

			<p>Pagani Imola</p>

		</div>

		<div class="card">

			<img src="img131.jpg" alt="Pagani Imola">

			<p>Pagani Imola</p>

		</div>

	</div>



	<footer>

		<h1>Kompanyalar</h1>

		<ul>

			<li><a href="https://youtube.com/@love_shortuz" target="_blank">Youtube</a></li>

			<li><a href="https://www.instagram.com/lazizbek.dev" target="_blank">Instagram</a></li>

			<li><a href="@Oxmurodov_L" target="_blank">Telegram</a></li>

			<li><a href="https://www.linkedin.com" target="_blank">LinkedIn</a></li>

		</ul>

	</footer>



	<!-- Modal (Popup) for "Kirish" -->

	<div id="loginModal" class="modal">

		<div class="modal-content">

			<span class="close">&times;</span>

			<h2>Kirish</h2>

			<form>

				<div class="form-group">

					<input type="text" placeholder="Foydalanuvchi nomi" required>

				</div>

				<div class="form-group">

					<input type="password" placeholder="Parol" required>

				</div>

				<div class="form-group">

					<input type="submit" value="Kirish">

				</div>

			</form>

		</div>

	</div>



	<!-- Modal (Popup) for "Yangilik" -->

	<div id="newsModal" class="modal">

		<div class="modal-content">

			<span class="close">&times;</span>

			<h2>Yangiliklar</h2>

			<p>

				Yangi web dizayn loyihalari ustida ishlash boshlandi.

				Saytning yangi interfeysi ishga tushirildi.

			</p>

		</div>

	</div>



	<!-- Modal (Popup) for "Ma'lumot" -->

	<div id="aboutModal" class="modal">

		<div class="modal-content">

			<span class="close">&times;</span>

			<h2>O'zim Haqimda</h2>

			<p>

				Men Oxmurodov Lazizbek, men O'zbekistonlik web dizayner va dasturchiman. 

				Men internet texnologiyalari va dizayn sohasida o'z bilimlarimni doimiy ravishda rivojlantiraman. 

				Agar sizda biror savol bo'lsa yoki biror loyiha ustida ishlashni istasangiz, men bilan bog'lanishdan tortinmang!

			</p>

		</div>

	</div>



	<!-- Modal (Popup) for "Bog'lanish" -->

	<div id="contactModal" class="modal">

		<div class="modal-content">

			<span class="close">&times;</span>

			<h2>Biz bilan bog'lanish</h2>

			<p>+998931685458</p>

			<h2>Telegram</h2>

			<p style="font-size: 30px">@Oxmurodov_L</p>

		</div>

	</div>



	<!-- JavaScript -->

	<script>

		// Modal oynalarini olish

		var loginModal = document.getElementById("loginModal");

		var newsModal = document.getElementById("newsModal");

		var aboutModal = document.getElementById("aboutModal");

		var contactModal = document.getElementById("contactModal");



		// Tugmalarni olish

		var loginBtn = document.getElementById("login-link");

		var newsBtn = document.getElementById("news-link");

		var aboutBtn = document.getElementById("about-link");

		var contactBtn = document.getElementById("contact-link");



		// "Kirish", "Yangilik", "Ma'lumot", "Bog'lanish" tugmalari uchun modal ko'rsatish

		loginBtn.onclick = function() {

			loginModal.style.display = "block";

		}

		newsBtn.onclick = function() {

			newsModal.style.display = "block";

		}

		aboutBtn.onclick = function() {

			aboutModal.style.display = "block";

		}

		contactBtn.onclick = function() {

			contactModal.style.display = "block";

		}



		// Modalni yopish uchun "X" tugmasi

		var closeBtns = document.getElementsByClassName("close");

		for (var i = 0; i < closeBtns.length; i++) {

			closeBtns[i].onclick = function() {

				loginModal.style.display = "none";

				aboutModal.style.display = "none";

				contactModal.style.display = "none";

				newsModal.style.display = "none";

			}

		}



		// Modal tashqarisiga bosganda uni yopish

		window.onclick = function(event) {

			if (event.target == loginModal || event.target == aboutModal || event.target == contactModal || event.target == newsModal) {

				loginModal.style.display = "none";

				aboutModal.style.display = "none";

				contactModal.style.display = "none";

				newsModal.style.display = "none";

			}

		}

	</script>



</body>

</html>

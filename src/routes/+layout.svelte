<head>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>

<script>
	let { children } = $props();
</script>

<body>
	<nav calss="navbar">
		<ul>
			<li>
				<a href="/">Origem</a>
			</li>
			<li>
				<a href="/Comportamento">Comportamento</a>
			</li>
			<li>
				<a href="/Aparência física">Aparência física</a>
			</li>
			<li>
				<a href="/Saúde">Saúde</a>
			</li>
			<li>
				<a href="/Preço">Preço</a>
			</li>
			<li>
				<a href="/Raças semelhantes">Raças semelhantes</a>
			</li>
		</ul>
		<hr />
	</nav>

	<footer>
	<hr /> 
		<h5>Compartilhe este site:</h5>
		<a><i class="bi bi-whatsapp"></i> Whatsapp  </a>
		<a><i class="bi bi-facebook"></i> Facebook  </a>
		<a><i class="bi bi-envelope"></i> e-mail </a>
		<a><i class="bi bi-twitter"></i> Twitter</a>
	</footer>
</body>

{@render children()}

<style>
	body {
		background-color: #37add1;
		font-family: Arial, Helvetica, sans-serif;
		margin-right: 20px;
	}

	ul {
		display: flex;
		justify-content: space-between;
		list-style-type: none;
		align-items: center;
		padding: 16px;
	}

	a {
		color: white;
		text-decoration: none;
	}

	h5{
		color:white;
	}
</style>

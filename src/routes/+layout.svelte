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
	</nav>


</body>

<style>


body{
	background-color:#37add1;
	font-family:Arial, Helvetica, sans-serif;
	margin-right: 20px;
}

.navbar{
	background-color: #333;
}

	ul{
		display:flex;
		justify-content: space-between;
		list-style-type: none;
		align-items: center;
		padding: 16px;

	}

	a{
		color:white;
		text-decoration: none;
	}

</style>

{@render children()}

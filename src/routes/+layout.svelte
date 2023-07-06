<h1>Švehlovka</h1>
<nav>
	<a href="/pro_novacky">Pro nováčky</a>
	<a href="">Ubytování</a>
	<a href="/sluzby">Služby</a>
	<a href="">Fotogalerie</a>
</nav>

<img src="https://i.imgur.com/jtS24vP.png" alt="Naše kolej" />

<main>
	<slot />
</main>

<style>
	:global(body) {
		display: flex;
		flex-direction: column;
		margin: 0;
		align-items: center;
	}

	h1 {
		text-align: center;
	}

	nav {
		display: flex;
		width: 100%;
		flex-direction: row;
		justify-content: space-around;
		background: lightcoral;
		padding: 10px;
		position: sticky;
		top: 0;
	}

	a {
		color: unset;
		text-decoration: none;
		font-weight: bold;
	}

	main {
		padding: 30px;
		max-width: 40em;
		text-align: justify;
	}
</style>

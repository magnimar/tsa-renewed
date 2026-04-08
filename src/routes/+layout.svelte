<script>
	import { base } from '$app/paths';
	import '../app.css';
	let { children } = $props();
</script>

<header>
	<div class="container">
		<div style="display: flex; justify-content: space-between; align-items: center;">
			<a
				href="{base}/"
				style="font-family: var(--font-serif); font-size: 1.5rem; font-weight: bold; color: var(--color-wood-dark);"
			>
				TSA
			</a>
			<nav>
				<ul>
					<li><a href="{base}/">Aðalsíða</a></li>
					<li><a href="{base}/um-tsa">Um okkur</a></li>
					<li><a href="{base}/myndir">Myndir</a></li>
					<li><a href="{base}/hafd-samband">Hafðu samband</a></li>
				</ul>
			</nav>
		</div>
	</div>
</header>

<main>
	{@render children()}
</main>

<footer>
	<div class="container">
		<p>&copy; {new Date().getFullYear()} TSA - Trésmíðaverkstæði Stefáns & Ara</p>
		<p>
			Brekkustígur 38, 260 Njarðvík | Sími: 421-2788 | <a href="mailto:tsa@tsa.is">tsa@tsa.is</a>
		</p>
	</div>
</footer>

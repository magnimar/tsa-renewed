<script>
	import { base } from '$app/paths';
</script>

<svelte:head>
	<title>TSA - Trésmíðaverkstæði Stefáns & Ara</title>
</svelte:head>

<section class="hero">
	<div class="container">
		<h1>TSA</h1>
		<p style="font-size: 1.5rem; color: var(--color-wood-medium);">
			Trésmíðaverkstæði Stefáns & Ara
		</p>
		<h2 style="margin-top: 2rem;">Velkomin(n) á heimasíðu TSA</h2>
		<p style="max-width: 600px; margin: 2rem auto;">
			Við bjóðum upp á alhliða trésmíðaþjónustu, allt frá nýsmíði og innréttingum til sérhæfðra
			verkefna fyrir stærri fyrirtæki og einstaklinga.
		</p>
		<div style="margin-top: 3rem;">
			<a
				href="{base}/um-tsa"
				class="button"
				style="background-color: var(--color-wood-dark); color: white; padding: 12px 24px; border-radius: 4px; font-weight: bold;"
				>Um okkur</a
			>
		</div>
	</div>
</section>

<section class="section">
	<div class="container">
		<div class="grid">
			<div style="text-align: center; padding: 20px;">
				<h3 style="font-family: var(--font-serif);">Gæði og Fagmennska</h3>
				<p>Við leggjum metnað í vönduð vinnubrögð og gæði í hvívetna.</p>
			</div>
			<div style="text-align: center; padding: 20px;">
				<h3 style="font-family: var(--font-serif);">Reynsla frá 1989</h3>
				<p>Áratuga reynsla í stórum og smáum verkefnum um allt land.</p>
			</div>
			<div style="text-align: center; padding: 20px;">
				<h3 style="font-family: var(--font-serif);">Traust þjónusta</h3>
				<p>Öryggi, áreiðanleiki og gott samstarf við okkar viðskiptavini.</p>
			</div>
		</div>
	</div>
</section>

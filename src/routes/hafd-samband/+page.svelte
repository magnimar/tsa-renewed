<svelte:head>
	<title>Hafðu samband - TSA - Trésmíðaverkstæði Stefáns & Ara</title>
</svelte:head>

<section class="section">
	<div class="container">
		<h1 style="text-align: center; margin-bottom: 3rem;">Hafðu samband</h1>

		<div class="grid">
			<div class="contact-info">
				<h2 style="border-bottom: 2px solid var(--color-wood-light); padding-bottom: 10px;">
					Upplýsingar
				</h2>

				<div class="info-item">
					<strong>Heimilisfang:</strong>
					<p>Brekkustígur 38, 260 Njarðvík</p>
				</div>

				<div class="info-item">
					<strong>Póstfang:</strong>
					<p>P.O. Box 197, 230 Keflavík</p>
				</div>

				<div class="info-item">
					<strong>Símanúmer:</strong>
					<ul>
						<li>Verkstæði / Skrifstofa: <a href="tel:4212788">421-2788</a></li>
						<li>Stefán: <a href="tel:8962788">896-2788</a></li>
						<li>Ari: <a href="tel:8940354">894-0354</a></li>
						<li>Garðar: <a href="tel:6952788">695-2788</a></li>
						<li>Fax: 421-6288</li>
					</ul>
				</div>

				<div class="info-item">
					<strong>Netfang:</strong>
					<p><a href="mailto:tsa@tsa.is">tsa@tsa.is</a></p>
				</div>

				<div class="info-item">
					<strong>Kennitala:</strong>
					<p>580189-1729</p>
				</div>
			</div>

			<div class="contact-form">
				<h2 style="border-bottom: 2px solid var(--color-wood-light); padding-bottom: 10px;">
					Sendu okkur línu
				</h2>
				<form onsubmit={(e) => e.preventDefault()}>
					<div class="form-group">
						<label for="name">Nafn</label>
						<input type="text" id="name" name="name" required />
					</div>
					<div class="form-group">
						<label for="email">Netfang</label>
						<input type="email" id="email" name="email" required />
					</div>
					<div class="form-group">
						<label for="subject">Viðfangsefni</label>
						<input type="text" id="subject" name="subject" />
					</div>
					<div class="form-group">
						<label for="message">Skilaboð</label>
						<textarea id="message" name="message" rows="5" required></textarea>
					</div>
					<button type="submit">Senda skilaboð</button>
				</form>
			</div>
		</div>
	</div>
</section>

<style>
	.info-item {
		margin-bottom: 25px;
	}

	.info-item strong {
		display: block;
		color: var(--color-wood-dark);
		margin-bottom: 5px;
	}

	.info-item p {
		margin: 0;
	}

	.form-group {
		margin-bottom: 20px;
	}

	label {
		display: block;
		margin-bottom: 5px;
		font-weight: bold;
		color: var(--color-wood-dark);
	}

	input,
	textarea {
		width: 100%;
		padding: 10px;
		border: 1px solid var(--color-wood-light);
		border-radius: 4px;
		font-family: inherit;
	}

	button {
		background-color: var(--color-wood-dark);
		color: white;
		padding: 12px 24px;
		border: none;
		border-radius: 4px;
		font-weight: bold;
		cursor: pointer;
		transition: background-color 0.2s;
	}

	button:hover {
		background-color: var(--color-accent);
	}
</style>

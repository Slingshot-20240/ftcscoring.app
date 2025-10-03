<script lang="ts">
	const ts = Date.now();
</script>

<svelte:head>
	<title>DECODE™ Scorer for FTC® | 20240 Slingshot</title>
	<link rel="canonical" href="https://ftcscoring.app/" />

	<meta
		name="description"
		content="Introducing the DECODE™ Scorer presented by 20240 Slingshot. The ultimate scorer, redefined for the 2025-2026 FIRST® Tech Challenge season."
	/>

	<meta property="og:url" content="https://ftcscoring.app" />
	<meta property="og:type" content="website" />
	<meta property="og:title" content="DECODE™ Scorer for FTC® | 20240 Slingshot" />
	<meta
		property="og:description"
		content="Introducing the DECODE™ Scorer presented by 20240 Slingshot. The ultimate scorer, redefined for the 2025-2026 FIRST® Tech Challenge season."
	/>
	<meta property="og:image" content="/ogp.jpg" />

	<meta name="twitter:card" content="summary_large_image" />
	<meta property="twitter:domain" content="ftcscoring.app" />
	<meta property="twitter:url" content="https://ftcscoring.app" />
	<meta name="twitter:title" content="DECODE™ Scorer for FTC® | 20240 Slingshot" />
	<meta
		name="twitter:description"
		content="Introducing the DECODE™ Scorer presented by 20240 Slingshot. The ultimate scorer, redefined for the 2025-2026 FIRST® Tech Challenge season."
	/>
	<meta name="twitter:image" content="/ogp.jpg" />

	<meta name="theme-color" content="#F4E3C5" />
</svelte:head>

<main>
	<h1>DECODE™ Scorer for the FIRST® Tech Challenge</h1>

	<img id="logo" src="/logo.png" alt="FTC Team 20240 Slingshot Logo" />

	<img
		id="gsv"
		src="/game-score-view.png"
		alt="Full game scoring view in the DECODE™ Scorer presented by 20240 Slingshot app"
	/>

	<h2>The ultimate scorer, <b>redefined.</b></h2>

	<h3>You've never seen a scorer like this.</h3>

	<a id="ios-download" target="_blank" href="/ios-download">
		{#if ts > 1759647600000}
			<img src="/ios-download-badge.svg" alt="Download on the Apple® App Store®" />
		{:else}
			<img src="/ios-preorder-badge.svg" alt="Pre-order on the Apple® App Store®" />
		{/if}
	</a>

	<a
		id="waitlist"
		href="mailto:beta@ftcscoring.app?subject=Android%20Beta%20Waitlist%20Request%20for%20the%20DECODE%E2%84%A2%20Scorer%20presented%20by%2020240%20Slingshot&body=This%20is%20an%20automatically%20generated%20request.%0A%0ABy%20sending%20this%20email%20request%2C%20you%20agree%20to%20receive%20further%20email%20communications%20from%20beta%40ftcscoring.app%20regarding%20the%20DECODE%E2%84%A2%20Scorer%20presented%20by%2020240%20Slingshot%20development%20and%20beta%20program."
		>Join the Android beta waitlist ↗</a
	>

	<div id="footnotes">
		<div>
			<a class="link" href="/ios-beta" target="_blank">iOS Beta ↗</a>
			<span>&nbsp;&nbsp;|&nbsp;&nbsp;</span>
			<a class="link" href="/ftc-app" target="_blank">FTC App ↗</a>
			<span>&nbsp;&nbsp;|&nbsp;&nbsp;</span>
			<a class="link" href="/github" target="_blank">GitHub ↗</a>
		</div>

		<div>
			<a class="link" href="/privacy">Privacy Policy</a>
			<span>&nbsp;&nbsp;|&nbsp;&nbsp;</span>
			<a class="link" href="/terms">Terms & Conditions</a>
		</div>
	</div>
</main>

<style>
	:global(:root, body) {
		margin: 0;
		padding: 0;
		width: 100vw;
		height: 100vh;
		background-color: #f4e3c5;
		background-image: url('/bg.png');
		background-size: 100%;
	}

	*,
	a,
	span {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
		font-family: Inter, sans-serif;
		text-decoration: none;
	}

	main {
		width: 100vw;
		min-height: 100vh;
		padding: 2rem;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		overflow-y: auto;

		h1 {
			position: absolute;
			opacity: 0;
			top: -100%;
			left: -100%;
		}

		#logo {
			width: min(8.8rem, 28%);
		}

		#gsv {
			margin: max(-1rem, -2%) 0 min(0.6rem, 3%) 0;
			width: min(52rem, 100%);
		}

		h2 {
			margin: calc(min(2.8rem, 8vw) / 3) 0 0.2rem 0;
			font-size: min(2.4rem, 7.2vw);
			font-weight: 300;
			text-align: center;

			b {
				font-weight: 600;
			}
		}

		h3 {
			margin: calc(min(1.6rem, 5vw) / 3) 0 0.2rem 0;
			font-size: min(1.4rem, 4.8vw);
			font-weight: 300;
			text-align: center;
		}

		#ios-download {
			margin: min(1.2rem, 4vw) 0 0 0;
			width: min(8rem, 32%);
			img {
				width: 100%;
			}
		}

		#waitlist {
			margin: min(1rem, 3.2vw) 0 0.2rem 0;
			transition: color 0.2s;
			font-size: min(1rem, 3.6vw);
			font-weight: 500;
			color: #000;

			&:hover {
				color: #836112;
			}
		}

		#footnotes {
			display: flex;
			flex-direction: column;
			align-items: center;
			margin-top: min(1.2rem, 4vw);

			div {
				display: flex;

				* {
					margin: 0.4rem 0 0.4rem 0;
					font-size: min(0.8rem, 3vw);
					color: #876;
					transition: color 0.2s;

					&.link:hover {
						color: #000;
					}
				}
			}
		}
	}
</style>

<head>
	<title>DECODE™ Scorer for FTC | 20240 Slingshot</title>
	<link rel="canonical" href="https://ftcscoring.app/" />
</head>

<main>
	<h1>DECODE™ Scorer for the FIRST® Tech Challenge</h1>

	<img id="logo" src="/logo.png" alt="FTC Team 20240 Slingshot Logo" />

	<img
		id="hs"
		src="/homescreen.png"
		alt="DECODE™ Scorer presented by 20240 Slingshot App Home Screen"
	/>

	<h2>The ultimate scorer, <b>redefined.</b></h2>

	<h3>You've never seen a scorer like this.</h3>

	<a id="ios-beta" target="_blank" href="https://testflight.apple.com/join/wJ6S1QpV"
		><span>Get the iOS beta</span></a
	>

	<a
		id="waitlist"
		href="mailto:beta@ftcscoring.app?subject=Android%20Beta%20Waitlist%20Request%20for%20the%20DECODE%E2%84%A2%20Scorer%20presented%20by%2020240%20Slingshot&body=This%20is%20an%20automatically%20generated%20request.%0A%0ABy%20sending%20this%20email%20request%2C%20you%20agree%20to%20receive%20further%20email%20communications%20from%20beta%40ftcscoring.app%20regarding%20the%20DECODE%E2%84%A2%20Scorer%20presented%20by%2020240%20Slingshot%20development%20and%20beta%20program."
		>Join the Android beta waitlist ↗</a
	>

	<div>
		<a class="link" href="/ftc-app" target="_blank">FTC App ↗</a>
		<span>&nbsp;&nbsp;|&nbsp;&nbsp;</span>
		<a class="link" href="https://itd.ftcscoring.app" target="_blank">INTO THE DEEP℠ Scorer ↗</a>
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
			margin: 0 0 calc(min(12rem, 40%) / 16) 0;
			width: min(12rem, 40%);
		}

		#hs {
			width: min(56rem, 100%);
		}

		h2 {
			margin: calc(min(2.8rem, 8vw) / 3) 0 0.2rem 0;
			font-size: min(2.8rem, 8vw);
			font-weight: 300;
			text-align: center;

			b {
				font-weight: 600;
			}
		}

		h3 {
			margin: calc(min(1.6rem, 5vw) / 3) 0 0.2rem 0;
			font-size: min(1.6rem, 5vw);
			font-weight: 300;
		}

		#ios-beta {
			margin: min(1.2rem, 4vw) 0 0.2rem 0;
			padding: calc(min(1.2rem, 4vw) / 3) calc(min(1.2rem, 4vw) / 2);
			background: linear-gradient(180deg, #1f1f1f 0%, #0f0f0f 100%);
			border-radius: calc(min(1.4rem, 4.2vw) / 2);
			transition: filter 0.2s;

			span {
				font-size: min(1.2rem, 4vw);
				font-weight: 600;
				color: #e5ae32;
				transition: filter 0.2s;
			}

			&:hover {
				filter: brightness(1.1);
			}
		}

		#waitlist {
			margin: min(1.2rem, 4vw) 0 0.2rem 0;
			transition: color 0.2s;
			font-size: min(1rem, 3.6vw);
			font-weight: 500;
			color: #000;

			&:hover {
				color: #836112;
			}
		}

		div {
			display: flex;

			* {
				margin: min(1.2rem, 4vw) 0 0.2rem 0;
				font-size: min(0.8rem, 3vw);
				color: #876;
				transition: color 0.2s;

				&.link:hover {
					color: #000;
				}
			}
		}
	}
</style>

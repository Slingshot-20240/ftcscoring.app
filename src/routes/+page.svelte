<main>
  <img id="logo" src="/logo.png" alt="FTC Team 20240 Slingshot Logo">

  <img id="hs" src="/homescreen.png" alt="DECODE™ Scorer presented by 20240 Slingshot App Home Screen">

  <h1>The ultimate scorer, <b>redefined.</b></h1>

  <h3>September 12</h3>
</main>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap');

	:global(:root, body) {
		margin: 0;
		padding: 0;
		width: 100vw;
		height: 100vh;
		font-family: 'Inter', sans-serif;
		background-color: #f4e3c5;
		background-image: url('/bg.png');
		background-size: 100%;
	}

	* {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
	}

	main {
		width: 100vw;
		height: 100vh;
    padding: 2rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    #logo {
      margin: 0 0 calc(min(12rem, 40%) / 16) 0;
      width: min(12rem, 40%);
    }

    #hs {
      width: min(60rem, 100%);
    }

    h1 {
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
	}
</style>

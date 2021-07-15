<script>

</script>

<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@500&display=swap" rel="stylesheet">
</svelte:head>

<main>
	<header>
		<div class="logo">
				<img style="width: 269px; margin-bottom: 10px;" src="assets/logo/logo.png" alt="logo" />
				<img style="width: 188px" src="assets/logo/Vector 1.png" alt="ul" />
		</div>
	</header>

	<nav>
		<div class="nav-sel">
			<select>
				<option value="">Japan</option>
			</select>			
		</div>

		<div class="nav-btn">
			<button>Food</button>
			<button>Life</button>
			<button>Culture</button>
			<button>Live</button>
			<button>Story</button>
		</div>
	</nav>

	<section>
		<div>
			<img style="width: 100%" src="assets/splash/bg.png" alt="splash" />
			<div style="position: absolute; top: 540px; left: 50px; display: flex; flex-direction: column; justify-content: space-evenly">
				<h1>人生の先輩に学ぶ<br/>生き方の学校</h1>
				<h2>School of Life,<br/>Learning from Legends</h2>
			</div>

		</div>
	</section>

	<section style="padding: 50px">
		<div style="display: flex; flex-direction: row; align-items: center; justify-content: center;">
			<img style="width: 269px" src="assets/faceL.png" alt="facel" />
			<h3>繋がり、学び、継なぐ</h3>
			<img style="width: 296px" src="assets/faceR.png" alt="facel" />
		</div>
	</section>

	<section style="padding: 25px; background-color: #F6F6F5">
		<h4>秘伝の味をつなぐ  | Passing on the secret taste</h4>
		<div class="vid" style="display: flex; flex-direction: row; align-items: center;">
			<img style="width: 234px" src="assets/video/Group 3.png" alt="group2" />
			<img style="width: 234px" src="assets/video/Group 2.png" alt="group2" />
			<img style="width: 234px" src="assets/video/Group 5.png" alt="group2" />
			<img style="width: 234px" src="assets/video/Group 7.png" alt="group2" />
			<img style="width: 234px" src="assets/video/Group 8.png" alt="group2" />
		</div>  
	</section>

	<section style="padding: 25px; background-color: #FBB500">
		<h4>人生にちょっぴり疲れたら  | Feeling a little tired of life?</h4>
		<div class="vid" style="display: flex; flex-direction: row; align-items: center;">
			<img style="width: 489px" src="assets/other/Group 4.png" alt="group2" />
			<img style="width: 489px" src="assets/other/Group 10.png" alt="group2" />
			<img style="width: 489px" src="assets/other/Group 11.png" alt="group2" />
		</div>  
	</section> 

	<section style="padding: 25px; background-color: #FFF">
		<h4>スタイルを大切に  | Learn about styles, cultures.</h4>
		<div class="vid" style="display: flex; flex-direction: row; align-items: center;">
			<img style="width: 234px" src="assets/culture/Group 25.png" alt="group2" />
			<img style="width: 234px" src="assets/culture/Group 30.png" alt="group2" />
			<img style="width: 234px" src="assets/culture/Group 35.png" alt="group2" />
			<img style="width: 234px" src="assets/culture/Group 36.png" alt="group2" />
		</div>  
	</section> 

	<section style="padding: 25px; background-color: #0E0E0E">
		<h4>人生にちょっぴり疲れたら  | Feeling a little tired of life?</h4>
		<div class="vid" style="display: flex; flex-direction: row; align-items: center;">
			<img style="width: 489px" src="assets/more/Group 31.png" alt="group2" />
			<img style="width: 489px" src="assets/more/Group 32.png" alt="group2" />
			<img style="width: 489px" src="assets/more/Group 33.png" alt="group2" />
		</div>  
	</section> 
</main>

<style>



	:global(body) {
		margin: 0;
		padding: 0;
		font-family: 'Quicksand', sans-serif;
		font-size: 18px;
		color: #54492B;
	}

	main {
		margin: 0;
		padding: 0;
	}

	header {
		/* background: grey; */
		display: flex;
		flex-direction: row;
		align-items: center;
		padding-left: 90px;
	}

	.logo {
		padding: 40px 0;
		display: flex;
		flex-direction: column;
		width: 269px;
		align-items: center;
	}

	nav {
		background-color: #FBB400;
		padding: 15px;
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: flex-start;
	}

	.nav-sel {
		margin: 0 40px;
	}

	nav .nav-sel select {
		width: 225px;
		height: 46px;
		background: #FFFFFF;
		border-radius: 23px;
	}

	nav .nav-btn button {

		width: 103px;
		height: 46px;
		border-radius: 23px;
		border-color: #54492B;
		background-color: #FBB400;
		margin: 0 5px;
	}

	h1 {
		font-size: 42px;
		color: #fff;
		margin: 10px 0;
	}
	h2 {
		font-size: 42px;
		color: #fff;
		margin: 10px 0;
	}
	h3 {
		font-size: 38px;
		color: #FBB500;
	}

	.vid img  {
		margin: 0 15px;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
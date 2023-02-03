<script>
	import '../app.css';
</script>

<main>
	<section class="grid">
		<div class="box">
			<div class="box-content">
				<p class="experience">Experience</p>
				<div>
					<p class="year">OCT 2017 - PRESENT</p>
					<p class="year">Backend developer cum team lead</p>
					<p class="company">Govicle Sdn Bhd</p>
					<p class="company-url">govicle.com.my</p>
				</div>
			</div>
		</div>
		<div class="box">
			<div class="box-content">
				<div>
					<p class="year">OCT 2017 - PRESENT</p>
					<p class="year">Backend developer cum team lead</p>
					<p class="company">Govicle Sdn Bhd</p>
					<p class="company-url">govicle.com.my</p>
				</div>
			</div>
		</div>
		<div class="box">
			<div class="box-content">
				<div>
					<p class="year">OCT 2017 - PRESENT</p>
					<p class="year">Backend developer cum team lead</p>
					<p class="company">Govicle Sdn Bhd</p>
					<p class="company-url">govicle.com.my</p>
				</div>
			</div>
		</div>
		<div class="box">
			<div class="box-content">
				<div>
					<p class="year">OCT 2017 - PRESENT</p>
					<p class="year">Backend developer cum team lead</p>
					<p class="company">Govicle Sdn Bhd</p>
					<p class="company-url">govicle.com.my</p>
				</div>
			</div>
		</div>
		<div class="box">
			<div class="box-content">
				<div>
					<p class="year">OCT 2017 - PRESENT</p>
					<p class="year">Backend developer cum team lead</p>
					<p class="company">Govicle Sdn Bhd</p>
					<p class="company-url">govicle.com.my</p>
				</div>
			</div>
		</div>
		<div class="box">
			<div class="box-content">
				<div>
					<p class="year">OCT 2017 - PRESENT</p>
					<p class="year">Backend developer cum team lead</p>
					<p class="company">Govicle Sdn Bhd</p>
					<p class="company-url">govicle.com.my</p>
				</div>
			</div>
		</div>
		<div class="box">
			<div class="box-content">
				<div class="interest">
					<p>Interests</p>
					<ul>
						<li>football</li>
						<li>games</li>
						<li>comics</li>
						<li>manga</li>
						<li>anime</li>
					</ul>
				</div>
				<div class="personal-details">
					<h1>Zaid</h1>
					<h4>Naim</h4>
					<p>Backend Developer cum Team Lead</p>
					<p>rawang, selangor</p>
					<p>+60-12507 8030</p>
					<p>m.naim.zaid@gmail.com</p>
					<p>www.naimzaid.com</p>
				</div>
				<img class="avatar" src="images/avatar-naim.jpg" alt="">
			</div>
		</div>
		<div class="box">
			<div class="box-content">Box 8</div>
		</div>
	</section>
</main>

<slot />

<style lang="scss">
	main {
		width: 100vw;
		display: flex;
		justify-content: space-around;
		color: white;

		section {
			width: 100%;
			/* max-width: 100%; */
			max-width: 832px;
			height: 100vh;
			/* max-height: 100%; */
			max-height: 450px;
			background: #313131;
		}
	}

	.grid {
		display: grid;
		/* grid-template-columns: 277px 277px 277px; */
		/* grid-template-columns: 1fr 1fr 1fr; */
		grid-template-columns: repeat(3, 1fr);
		grid-template-rows: repeat(4, 1fr);

		.box {
			&:nth-child(1) {
				background: green;
			}
			&:nth-child(2) {
				background: green;
			}
			&:nth-child(3) {
				background: green;
			}
			&:nth-child(4) {
				background: green;
			}
			&:nth-child(5) {
				background: green;
			}
			&:nth-child(6) {
				background: green;
			}
			&:nth-child(7) {
				background: yellow;
				grid-column: 1/3;
				grid-row: 2/4;
			}
			&:nth-child(8) {
				background: blue;
				grid-column: 1/3;
				grid-row: 4/5;
			}
			.box-content {
				display: flex;
				align-items: flex-start;
				.experience {
					writing-mode: vertical-rl;
					direction: ltr;
					transform: rotate(180deg);
				}

				img{
					width: 107px;
					height: 142px;
					border-radius: 10%;
					margin: 0 0 0 10px;
				}
				
			}
		}
	}
</style>

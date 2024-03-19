<div class="about">
	<div class="content">

		<div class="decor1">
			<img src={decoration1}/>
		</div>
		<div class="decor2">
			<img src={decoration2}/>
		</div>

		<div class="logo-img-div">
			<img src={logo} class="logo-img"/>


		</div>

		<div class="content2">
			<div class="content-top">
			<div class="tagline">Learn world-changing words and master their mind-bending effects.</div>

			<div class="div-video">
				<div class="video">
					<iframe class="video-iframe"
							src="https://www.youtube.com/embed/dyzWGS8ZT5Q">
					</iframe>
				</div>
			</div>

			<div class="steam-embed-pc">
				<iframe src="https://store.steampowered.com/widget/2207440/" frameborder="0" width="646" height="190"></iframe>
			</div>



			<div class="steam-embed-mobile">
				<img src={steam_logo} class="steam-img"/>
				<u>LOK Digital on Steam</u>
			</div>


			<form action="https://secure.draknek.org/sendy/subscribe" method="POST" accept-charset="utf-8">
				<input type="email" name="email" id="email" class="email" placeholder="email address" required />
				<div style="position: absolute; left: -5000px;">
					<label for="hp">HP</label><br/>
					<input type="text" name="hp" id="hp"/>
				</div>
				<input type="hidden" name="list" value="hJp8h763x9G9E8Ujj43DTVwA"/>
				<input type="hidden" name="subform" value="yes"/>
				<input type="submit" name="submit" id="submit" class="button-primary" value="Subscribe to updates"/>
			</form>
			</div>


			<div class="separator">

			</div>

			<a href="/presskit">
				<div class="presskit-link">
					PRESSKIT >
				</div>
			</a>

			<a href="mailto:hello@lok-digital.com">
				<div class="contact-link">
					CONTACT US >
				</div>
			</a>

			<div class="separator">

			</div>



			<div class="book-duet">
				<img src={book} class="book-img"/>
				<div class="book-duet-text">
					An adaptation of the acclaimed pen&paper puzzle book LOK
					<a href="https://www.blazgracar.com/lok">
						<div class="book-link">
							ABOUT THE BOOK >
						</div>
					</a>
				</div>

			</div>

			<div class="credits-middle">
				<div class="credit1">
					<div>
						Publishing
					</div>
					<div class="credits-middle-img-div">
						<img src={credits2} class="credits-middle-img"/>
					</div>
					<div class="credits-middle-link">
						<a href="https://www.draknek.org/">
							WEBSITE >
						</a>
					</div>
				</div>
				<div class="credit2">
					<div>
						Design
					</div>
					<div class="credits-middle-img-div">
						<img src={credits_letibus} class="credits-middle-img"/>
					</div>
					<div class="credits-middle-link">
						<a href="https://www.blazgracar.com/letibus">
							WEBSITE >
						</a>
					</div>
				</div>
				<div class="credit3">
					<div>
						Development
					</div>
					<div class="credits-middle-img-div">
						<img src={credits_icedrop} class="credits-middle-img"/>
					</div>
					<div class="credits-middle-link">
						<a href="https://www.icedropgames.com/">
							WEBSITE >
						</a>
					</div>
				</div>
			</div>




			<div class="content2-blurb">
				Embark on a whimsical puzzle solving journey of discovering unrecognizable words,
				each with their own special powers.<br>
				Find and spell these never-before-seen words, each with their own mind-bending ability to help change the world around you.
				<br><br>
				Learn the rules as you go and uncover how each magical word can be utilized to your advantage. <br>Uncover deep and thoughtful mechanics that will challenge and delight you as you uncover LOK’s unexpected twists and surprises.

			</div>
		</div>
	</div>


</div>

<svelte:head>
	<style>
		#header {
			display: none;
		}
	</style>
</svelte:head>

<script>
	import logo from '$lib/images/lok-digital/logo.png';
	import book from '$lib/images/book.png';
	import credits_icedrop from '$lib/images/lok-digital/credits_icedrop.png';
	import credits_letibus from '$lib/images/lok-digital/credits_letibus.png';
	import credits2 from '$lib/images/lok-digital/DraknekFriendsLogo.png';
	import steam_logo from '$lib/images/steam.png';
	import decoration1 from '$lib/images/lok-digital/decoration1.png';
	import decoration2 from '$lib/images/lok-digital/decoration2.png';

</script>

<style>

	.about {
		display: flex;
		flex-direction: column;
		align-items: center;

		width: 100%;

		font-family: CenturyLocal;

		background: #EEEEEE url("images/lok-bg.jpeg");
		background-size: 600px;

		position: relative;
	}

	.content {
		position: relative;
		align-items: center;
		justify-content: center;
		display: flex;
		flex-direction: column;
	}

	.content2 {

		background-color: white;

		-webkit-box-shadow: 0px 3px 9px 2px rgba(0,0,0,0.4);
		box-shadow: 0px 3px 9px 2px rgba(0,0,0,0.4);
		align-items: center;
		justify-content: center;

		display: flex;
		flex-direction: column;
		align-items: center;
	}

	.logo-img-div {
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.logo-img {
		max-width: 400px;
	}

	.text {

		text-align: justify;

		font-size: 1.15em;

		color: #333333;
	}

	.credits-img {
		max-width: 200px;
	}

	.images {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		align-content: stretch;
		padding-top: 32px;
		padding-bottom: 32px;
	}

	.image-box {
		max-width: 50%;
		display: flex;
	}

	.image-box-pad {
		padding: 8px;
		padding-bottom: 0px;
		padding-top: 6px;
		width: 100%;
	}

	.screenshot-img {
		border: 4px solid black;
		flex-shrink: 1;
		width: 100%;
	}

	.footer {
		display: flex;
		padding-left: 32px;
		padding-right: 16px;
		padding-bottom: 16px;
	}

	.footer-img {
		display: flex;
		align-items: center;
		justify-content: center;
		flex-grow: 0;
	}
	.empty {
		flex-grow: 1;
		min-width: 64px;
	}

	@media (max-width: 1250px) {
		.content {
			max-width: 90%;
			position: relative;
			padding: 0 !important;
		}
		.text {

			font-size: 1em;
		}

		.footer {
			flex-direction: column;
		}

		.video {
			max-width: 80vw;
		}

		.video-iframe {
		}

		.content2 {
			max-width: 85% !important;
		}

		.book-duet {
			flex-direction: column !important;
		}


	}

	@media (max-width: 900px) {
		.steam-embed-pc {
			display: none;
		}

		.steam-embed-mobile {
			display: flex !important;
		}

		.content {
			max-width: 100% !important;
		}

		.content2 {
			max-width: 100% !important;
		}
	}

	.decor1 {
		position: absolute;
		top: 250px;
		left: -500px;
		scale: 1;
	}

	.decor2 {
		position: absolute;
		top: 1000px;
		right: -550px;
		scale: 1;
	}

	.tagline {
		font-size: 1.5em;
		font-weight: bold;
		padding-bottom: 64px;
	}

	.div-video {
		padding-bottom: 64px;
		position: relative;
		width: 100%;
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.video {
		position: relative;
		padding-bottom: 56%;
		width: 100%;
		text-align: left;
		max-width: 646px;
	}

	.video-iframe {
		width: 100%;
		position: absolute;
		height: 100%;
		overflow: hidden;
	}

	.content2-blurb {
		padding-top: 16px;
		padding-bottom: 16px;
		text-align: left;
		text-align: justify;

		font-size: 1.15em;

		color: #333333;
		display: none;
	}

	.steam-embed {
		padding-bottom: 64px;
	}

	.presskit-link {
		font-family: CenturyLocal;
		font-weight: bold;
		font-size: 2em;
		margin-top: 32px;
		margin-bottom: 32px;
	}

	.contact-link {
		font-family: CenturyLocal;
		font-weight: bold;
		font-size: 1.5em;
		margin-top: 16px;
		margin-bottom: 64px;
	}

	.steam-img {
		max-width: 64px;
	}

	.steam-embed-mobile {
		font-weight: bold;
		display: flex;
		flex-direction: column;
		align-items: center;
		margin-top: 32px;
		margin-bottom: 32px;
		display: none;
	}

	.steam-embed-pc {
		margin-bottom: 64px;
	}

	.book-img {
		max-width: 300px;
	}

	.book-duet {
		display: flex;
		align-items: center;
	}

	.book-duet-text {
		font-size: 1.2em;
		max-width: 400px;
		padding-top: 64px;
	}

	.book-link {
		font-family: CenturyLocal;
		font-weight: bold;
		font-size: 1.2em;
		margin-top: 16px;
		margin-bottom: 64px;
	}

	.button-primary {
		background-color: black;
		color: white;
		border-radius: 8px;
		cursor: pointer;
	}

	.button-primary:hover {
		background-color: #333333;
	}

	.separator {
		width: 100%;
		height: 16px;
		background-color: #333333;
		margin-bottom: 32px;
		margin-top: 32px;
	}

	.content-top {
		padding: 64px;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		max-width: 100%;
	}

	.credits-middle {
		display: flex;
		width: 100%;
		align-items: center;
		justify-content: center;
		font-size: 1.2em;
		padding-bottom: 64px;
		padding-top: 32px;
		row-gap: 32px;
		column-gap: 64px;
		font-weight: bold;
	}

	.credits-middle-img-div {
		height: 150px;
		width: 200px;
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.credits-middle-img {
		max-width: 100%;
		max-height: 100%;
	}


</style>
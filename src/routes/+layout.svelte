<script>
	export let name;
</script>

<main>
	<div class="content">
		<slot/>
	</div>
</main>

<style>

	:global(body) {
		margin: 0;
	}

	main {
		text-align: center;
		padding: 0;
		margin: 0 0;
		height: 100%;
		overflow: hidden;

		background-color: #1E2026;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	.main-body{
		background-color: #1E2026;
		height: 100%;
		display: flex;
		flex-direction: column;
		color: #C0D6E2;
	}

	.header {
		padding: 1em;
	}

	.nav-menu {
		display: flex;
		position: relative;
	}

	.menu-option {
		font-weight: bold;
		font-size: 1.5em;
		padding: 0.5em;
		margin: 0.5em;
	}

	.filler {
		flex-grow: 1;
	}

	.content {
		display: flex;
		align-items: center;
		justify-content: center;
		overflow-y: clip;
	}

	.menu-left, .menu-right {
		width: 30%;
		display: flex;
		max-width: 100%;
		flex-direction: row;

		white-space: nowrap;
	}

	.menu-right {
		justify-content: right;
	}

	@media only screen and (max-width: 1100px) {

		.menu-left {
			flex-direction: column;
			justify-content: left;
			align-items: start;
		}

		.menu-left .menu-option {
			padding-top: 0;
			padding-bottom: 0;
		}

	}

	@media only screen and (max-width: 800px) {

		.menu-right, .menu-left {
			justify-content: center;
			font-size: 16px;
			flex-wrap: nowrap;
		}

		.filler {
			flex-grow: 0;
		}

		.nav-menu {
			flex-direction: column;
			align-items: center;
			justify-content: center;
		}

		.menu-option {
			margin: 0.2em 0.4em !important;
			padding: 0.2em 0.4em !important;
		}

		.menu-left {
			flex-direction: row;
			justify-content: center;
			align-items: center;
		}

	}



	.logo_top {
		height: 100px;
		padding-top: 8px;
	}

	.logo_top:hover {
		cursor: pointer;
	}

	.social {
		padding: 1em;
	}

	.social img {
		width: 32px;
		filter: invert(94%) sepia(2%) saturate(4420%) hue-rotate(174deg) brightness(89%) contrast(100%);
		cursor: pointer;

		transition: 0.1s;
	}

	.social img:hover {
		transform: scale(1.1);
		filter: invert(100%);
	}

	.menu-option-link:hover {
		color: white;
	}
	@font-face {
		font-family: 'CenturyLocal';
		font-style: normal;
		font-weight: 500;
		src: local(''), url('/font/Century.TTF') format('embedded-opentype'),
			/* IE6-IE8 */ url('/font/Century.TTF') format('woff2'),
			/* Super Modern Browsers */ url('/font/Century.TTF') format('woff'),
			/* Modern Browsers */ url('/font/Century.TTF') format('truetype'),
			/* Safari, Android, iOS */ url('/font/Century.TTF') format('svg'); /* Legacy iOS */
	}



</style>
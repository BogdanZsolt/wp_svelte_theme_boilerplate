<script>
	let name = 'Zsolt'
</script>

<div class="container">
	<h1>Hello {name}</h1>
</div>

<style lang="scss">
	.container {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;

		h1 {
			color: #ff3e00;
			text-transform: capitalize;
			font-size: 10rem;
			font-weight: 100;
		}
	}


	@media (min-width: 640px) {
		.container {
			max-width: none;
		}
	}
</style>
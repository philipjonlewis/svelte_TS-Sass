<script lang="ts">
	export let name: string;
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	<div class="trial">
		<p>
			My name is kinemelyn
		</p>
		<div class="nested">
			<h1>Hello There</h1>
		</div>
	</div>
</main>

<style lang="scss">
	.trial {
		p {
			color : blue;
			font-size: 1rem;
		}

		.nested {
			h1 {
				color : yellow;
			}
		}
	}
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
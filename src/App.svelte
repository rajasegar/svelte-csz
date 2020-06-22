<script>
        import csz from 'csz';
	const message = 'Learn Svelte';
</script>

<!-- <style>
	:global(body) {
		margin: 0;
		font-family: Arial, Helvetica, sans-serif;
	}
	.App {
		text-align: center;
	}
	.App-header {
		background-color: #F9F6F6;
		color: #333;
		min-height: 100vh;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		font-size: calc(10px + 2vmin);
	}
	.App-link {
		color: #ff3e00;
	}
	.App-logo {
		height: 40vmin;
		pointer-events: none;
		margin-bottom: 1.0rem;
		animation: App-logo-spin infinite 1.6s ease-in-out alternate;
	}
	@keyframes App-logo-spin {
		from {
			transform: scale(1);
		}
		to {
			transform: scale(1.06);
		}
	}
</style> -->

<div class={csz`
	:global(body) {
		margin: 0;
		font-family: Arial, Helvetica, sans-serif;
	}

text-align:center;
`}>
	<header class={csz`
                background-color: #F9F6F6;
		color: #333;
		min-height: 100vh;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		font-size: calc(10px + 2vmin);
        `}>
		<img src="/logo.svg" class={csz`

                @keyframes App-logo-spin {
		from {
			transform: scale(1);
		}
		to {
			transform: scale(1.06);
		}
                }

		height: 40vmin;
		pointer-events: none;
		margin-bottom: 1.0rem;
		animation: App-logo-spin infinite 1.6s ease-in-out alternate;

               	
                `} alt="logo" />
		<p>
			Edit <code>src/App.svelte</code> and save to reload.
		</p>
		<a
			class={csz`color:#ff3e00;`}
			href="https://svelte.dev"
			target="_blank"
			rel="noopener noreferrer"
		>
			{message}
		</a>
	</header>
</div>

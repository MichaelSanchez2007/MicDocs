<script>
	import Header from "$lib/Header.svelte"
</script>

<Header />

<slot />

<style global>
	@import url('https://fonts.googleapis.com/css2?family=Teko:wght@500&family=Tajawal:wght@400;500;700&display=swap');
	:global(h2) {
		font-size: 1.5rem;
		text-align: center;
		font-family: 'Teko', cursive;
      	margin-top: 0;
		letter-spacing: 2px;
		
   	}
	:global(*) {
		font-family: 'Tajawal', sans-serif;
	}

</style>
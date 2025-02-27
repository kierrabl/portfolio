<script>
	function navigate(section) {
		console.log(`Navigating to ${section}`);
	}
</script>

<!-- Page Content -->
<main class="min-h-screen bg-gray-200">
  	<h1 class="text-4xl font-bold text-black">Kierra Blankespoor</h1>

  	<div class="mt-6 space-x-4">

    	<button class="px-4 py-2 bg-transparent text-black rounded-lg shadow-md" on:click={() => navigate('about')}>
      		About
    	</button>

    	<button class="px-4 py-2 bg-transparent text-black rounded-lg shadow-md" on:click={() => navigate('experience')}>
     		Experience
    	</button>

    	<button class="px-4 py-2 bg-transparent text-black rounded-lg shadow-md" on:click={() => navigate('projects')}>
      		Projects
    	</button>

  	</div>
</main>
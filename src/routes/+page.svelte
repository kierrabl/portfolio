<script>
	function navigate(section) {
		console.log(`Navigating to ${section}`);
	}
</script>

<!-- Page Content -->
<main class="min-h-screen bg-gray-200">

  	<div class="pt-6 pr-6 min-h-screeen bg-gray-200 text-right">

    	<button class="px-4 py-2 bg-transparent font-['Quicksand', 'sans-serif'] text-black rounded-lg shadow-md" on:click={() => navigate('about')}>
      		About
    	</button>

    	<button class="px-4 py-2 bg-transparent font-['Quicksand', 'sans-serif'] text-black rounded-lg shadow-md" on:click={() => navigate('experience')}>
     		Experience
    	</button>

    	<button class="px-4 py-2 bg-transparent font-['Quicksand', 'sans-serif'] text-black rounded-lg shadow-md" on:click={() => navigate('projects')}>
      		Projects
    	</button>

  	</div>

	<h1 class="mt-6 text-7xl font-['Lora',serif] font-bold text-black text-center">Kierra Blankespoor</h1>

</main>
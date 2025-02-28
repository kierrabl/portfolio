<script>
	function navigate(section) {
		console.log(`Navigating to ${section}`);
	}
</script>

<!-- Page Content -->
<main class="min-h-screen bg-gray-200">

	<!-- Navbar Container -->
	<div class="flex items-center justify-between p-4">
		<!-- Logo -->
		<img src="/logo.png" alt="K Logo" class="h-10 w-auto" />
	
		<!-- Button Group -->
		<div class="flex space-x-6">
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
	  </div>

	<img src="/name.png" alt="Kierra Blankespoor" class="block mx-auto h-80 w-auto" />

</main>
<script>
	import { onMount } from 'svelte';
</script>

<nav class="w-full py-5 border-b border-transparent">
	<div class="container flex items-center justify-between">
		<!-- Logo -->
		<a href="/" class="flex items-center text-black">
			<svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
				<circle cx="12" cy="12" r="2.5" fill="currentColor"/>
				<circle cx="12" cy="5" r="2.5" fill="currentColor"/>
				<circle cx="12" cy="19" r="2.5" fill="currentColor"/>
				<circle cx="5" cy="12" r="2.5" fill="currentColor"/>
				<circle cx="19" cy="12" r="2.5" fill="currentColor"/>
			</svg>
		</a>

		<!-- Links -->
		<div class="hidden lg:flex items-center gap-8 text-[13px] font-medium text-gray-700">
			<a href="#" class="text-black hover:text-black transition-colors">Sana Learn</a>
			<a href="#" class="hover:text-black transition-colors">Solutions</a>
			<a href="#" class="hover:text-black transition-colors">Partner stories</a>
			<a href="#" class="hover:text-black transition-colors">Integrations</a>
			<a href="#" class="hover:text-black transition-colors">Events</a>
			<a href="#" class="hover:text-black transition-colors">Pricing</a>
		</div>

		<!-- Button -->
		<a href="#" class="bg-[#0055FF] text-white text-[13px] font-medium px-4 py-2 rounded-full hover:bg-blue-700 transition-colors">
			Book an intro
		</a>
	</div>
</nav>

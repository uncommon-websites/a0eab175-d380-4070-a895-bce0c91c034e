<script lang="ts">
	export let label: string = "";
	export let quote: string;
	export let authorName: string;
	export let authorRole: string;
	export let authorImage: string;
	export let buttonText: string = "Read the case study";
</script>

<section class="py-24 border-b border-gray-100">
	<div class="container grid grid-cols-1 lg:grid-cols-12 gap-12">
		{#if label}
			<div class="lg:col-span-3">
				<span class="text-sm text-gray-500">{label}</span>
			</div>
		{:else}
			<div class="lg:col-span-3"></div>
		{/if}

		<div class="lg:col-span-9 flex flex-col gap-10">
			<h2 class="text-[2.5rem] leading-[1.1] font-serif text-black max-w-3xl">
				{quote}
			</h2>

			<div class="flex items-center gap-4">
				<img src={authorImage} alt={authorName} class="w-12 h-12 rounded-lg object-cover bg-gray-200" />
				<div class="flex flex-col">
					<span class="text-[15px] font-medium text-black">{authorName}</span>
					<span class="text-[15px] text-gray-500">{authorRole}</span>
				</div>
			</div>

			<div>
				<a href="#" class="inline-flex items-center justify-center bg-black text-white px-6 py-3 rounded-full text-sm font-medium hover:bg-gray-800 transition-colors">
					{buttonText}
				</a>
			</div>
		</div>
	</div>
</section>

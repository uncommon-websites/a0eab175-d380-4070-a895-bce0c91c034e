<script>
	const faqs = [
		{ question: "Does Sana integrate with Salesforce or other CRMs?", open: false },
		{ question: "Are the CRM integrations native or via API?", open: false },
		{ question: "Can I record a pitch in Sana and get feedback or AI insights?", open: false },
		{ question: "How can we offer just-in-time learning for the sales team?", open: false },
		{ question: "Does Sana have CMS functionalities?", open: false }
	];
</script>

<section class="py-24 border-b border-gray-100">
	<div class="container grid grid-cols-1 lg:grid-cols-12 gap-12">
		<div class="lg:col-span-5">
			<h2 class="text-[3.5rem] leading-[1] font-serif text-black">
				FAQ
			</h2>
		</div>

		<div class="lg:col-span-7">
			<div class="divide-y divide-gray-100">
				{#each faqs as faq}
					<div class="py-6 flex justify-between items-center cursor-pointer group">
						<span class="text-[15px] text-black group-hover:text-gray-600 transition-colors">{faq.question}</span>
						<span class="text-xl font-light text-black">+</span>
					</div>
				{/each}
			</div>
		</div>
	</div>
</section>

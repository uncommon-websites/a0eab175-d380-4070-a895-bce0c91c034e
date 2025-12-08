<section class="py-24 border-b border-gray-100">
	<div class="container grid grid-cols-1 lg:grid-cols-12 gap-12">
		<div class="lg:col-span-5">
			<h2 class="text-[3.5rem] leading-[1] font-serif text-black max-w-sm">
				Enable more than your sales team
			</h2>
		</div>

		<div class="lg:col-span-7">
			<p class="text-[15px] text-gray-600 leading-relaxed mb-16 max-w-2xl">
				Sana isn't just for your sales training. It's the one home for all your company's learning and knowledge sharing—from compliance training and employee onboarding to leadership development and beyond.
			</p>

			<div class="space-y-4 mb-16">
				<div class="text-lg font-medium text-black border-b border-gray-100 pb-4">Compliance training</div>
				<div class="text-lg font-medium text-black border-b border-gray-100 pb-4">Employee onboarding</div>
				<div class="text-lg font-medium text-black border-b border-gray-100 pb-4">External training</div>
				<div class="text-lg font-medium text-black border-b border-gray-100 pb-4">Leadership development</div>
			</div>

			<div class="flex gap-3 overflow-x-auto pb-4">
				<!-- Badges -->
                {#each Array(5) as _}
				<div class="flex-shrink-0 w-20">
                    <svg viewBox="0 0 100 120" class="w-full h-auto drop-shadow-sm">
                        <!-- Badge shape -->
                        <path d="M50 115 L10 95 L10 25 L50 5 L90 25 L90 95 Z" fill="#F8F8F8" stroke="#E5E7EB" stroke-width="2"/>
                        <!-- Top colored part -->
                        <path d="M10 25 L50 5 L90 25 L90 45 L10 45 Z" fill="#FF4F00"/>
                        <!-- Text lines -->
                        <rect x="30" y="55" width="40" height="4" rx="2" fill="#E5E7EB"/>
                        <rect x="25" y="65" width="50" height="4" rx="2" fill="#E5E7EB"/>
                        <rect x="35" y="75" width="30" height="4" rx="2" fill="#E5E7EB"/>
                        <!-- Year -->
                        <rect x="30" y="90" width="40" height="10" rx="2" fill="#333"/>
                    </svg>
                </div>
                {/each}
			</div>
		</div>
	</div>
</section>

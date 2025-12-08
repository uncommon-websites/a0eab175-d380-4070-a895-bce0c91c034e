<script lang="ts">
	import Navbar from "$lib/components/Navbar.svelte";
	import Hero from "$lib/components/Hero.svelte";
	import Logos from "$lib/components/Logos.svelte";
	import Testimonial from "$lib/components/Testimonial.svelte";
	import StatsCards from "$lib/components/StatsCards.svelte";
	import Features from "$lib/components/Features.svelte";
	import AdditionalInfo from "$lib/components/AdditionalInfo.svelte";
	import FAQ from "$lib/components/FAQ.svelte";
	import Contact from "$lib/components/Contact.svelte";
	import Footer from "$lib/components/Footer.svelte";
</script>

<main class="bg-white min-h-screen">
	<Navbar />
	<Hero />
	<Logos />
	
	<div class="container">
		<span class="text-sm text-gray-500 block mt-24 mb-4">Sales enablement ROI</span>
	</div>
	
	<Testimonial 
		label=""
		quote="“We've saved a tremendous amount of time and money, and now we can guarantee that our sales representatives will get the most up-to-date training in time.”"
		authorName="Louise Henriksson"
		authorRole="Content and Planning Manager at Polestar"
		authorImage="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?q=80&w=100&auto=format&fit=crop"
		buttonText="Read the case study"
	/>
	
	<StatsCards />
	<Features />
	
	<Testimonial 
		label=""
		quote="“Thanks to Sana, everyone in sales can access the foundational knowledge they need. The sales rep experience is much more engaging and collaborative now.”"
		authorName="John Thornberg"
		authorRole="Commercial Excellence at AddLife"
		authorImage="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?q=80&w=100&auto=format&fit=crop"
		buttonText="Read the case study"
	/>
	
	<AdditionalInfo />
	<FAQ />
	<Contact />
	<Footer />
</main>


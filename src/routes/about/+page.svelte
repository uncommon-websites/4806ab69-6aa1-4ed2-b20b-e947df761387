<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Data-driven decisions",
			description: "We believe every reseller deserves access to the same market intelligence that top sellers use to stay ahead."
		},
		{
			title: "Side hustle success",
			description: "Built by resellers, for resellers. We understand the hustle because we've lived it—every feature serves real seller needs."
		},
		{
			title: "No guesswork",
			description: "Skip the endless scrolling and manual research. We surface the trends and pricing insights that actually move your business forward."
		},
		{
			title: "Trusted insights",
			description: "From pricing to sourcing, our real-time marketplace data helps over 10,000 resellers make confident decisions every day."
		}
	];
</script>

<SecondaryHero
	title="Sell smarter. Earn faster."
	subtitle="Real market insights for Vinted resellers."
	imageSrc="/generated/image-a-group-of-professionals-engaged-in-a-co.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We started Vinted Insights after struggling to grow our own resale side hustles. Hours were lost hunting for trends, guessing at pricing, and missing sales—just because data wasn't easy to find. We knew we weren't the only ones wasting time on blind decisions.",
		"So we built the tool we always wished we had. Vinted Insights scans Vinted's marketplace in real-time, tracking trending items, optimal pricing, and top-performing categories. No guesswork. No spreadsheets. Just clear insights built specifically for resellers who want to stay one step ahead of the market—and their competition.",
		"Today, our mission is simple: help 10,000+ resellers make smarter, faster decisions that grow their profits. Whether you're flipping fashion for fun or scaling a serious business, Vinted Insights aims to be your competitive edge. This is just the beginning."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our team."
	subtitle="Your partners in innovation."
	stakeholders={[
		{
			name: "Alex Morgan",
			position: "Founder & CEO",
			bio: "Started the company with a vision to transform the industry through innovative solutions.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Jamie Chen",
			position: "Chief Design Officer",
			bio: "Award-winning designer with a passion for creating intuitive and beautiful experiences.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Taylor Wright",
			position: "Head of Engineering",
			bio: "Technology enthusiast focused on building scalable systems that make a difference.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<StakeholderGrid
	stakeholderType="investor"
	title="Backed by the best."
	subtitle="Point Nine, TSIC and others"
	stakeholders={[
		{
			name: "Point Nine Capital",
			image: "https://cdn.brandfetch.io/pointnine.com/w/400/h/400/logo?c=1id_elLz2Bd5Ej-dWo7"
		},
		{
			name: "TSIC Ventures",
			image: "https://cdn.brandfetch.io/tiny.vc/w/400/h/400/logo?c=1a2b3c4d5e"
		},
		{
			name: "Sequoia Capital",
			image: "https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Stop guessing. Start growing."
	subtitle="Get Vinted insights that actually work"
	description="Join 10,000+ resellers who use real-time marketplace data to spot trends, price competitively, and maximize their side hustle profits. No more endless scrolling—just smart decisions."
/>

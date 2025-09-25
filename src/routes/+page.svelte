<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Turn Vinted data into profitable insights"
	subtitle="Stop manually researching trends and pricing. Get the competitive intelligence you need to maximize profits and scale your reseller business."
	imageSrc="/generated/image-a-confident-woman-carefully-sorting-and-.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by resellers scaling their business"
	logoUrls={[
		'https://cdn.brandfetch.io/vinted.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/etsy.com/w/400/h/400/logo', 
		'https://cdn.brandfetch.io/shopify.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/depop.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Making reselling profitable"
	text="We transform complex marketplace data into actionable insights that help Vinted resellers identify trending items, optimize pricing, and maximize profits. Our analytics platform eliminates guesswork, so you can scale your side hustle into a thriving business with confidence."
/>

<Testimonials
	testimonials={[
		{
			name: "Maya Chen",
			position: "Vintage Clothing Reseller",
			company: "MayaStyle Vintage",
			quote:
				"Before Vinted Insights, I spent 3 hours daily researching pricing and trends. Now it takes 15 minutes.\nI've increased my profit margins by 45% and can focus on sourcing quality pieces instead of endless data analysis.",
			image: "/generated/image-professional-headshot-of-an-asian-woman-.webp"
		},
		{
			name: "Carlos Rodriguez",
			position: "Part-time Reseller",
			company: "Weekend Finds",
			quote:
				"The competitive intelligence saved me from buying items that wouldn't sell. Last month alone, I avoided $800 in dead inventory.\nThe trend predictions helped me stock up on 90s sportswear before it exploded, making €2,400 profit in two weeks.",
			image: "/generated/image-professional-headshot-of-a-hispanic-man-.webp"
		},
		{
			name: "Keisha Williams",
			position: "Full-time Reseller",
			company: "Keisha's Closet",
			quote:
				"The pricing optimization tool automatically adjusts my listings based on market demand. My items sell 60% faster now.\nI've scaled from €500 to €3,200 monthly revenue in just 4 months using the platform's insights.",
			image: "/generated/image-professional-headshot-of-a-confident-bla.webp"
		}
	]}
/>

<Features
	title="Unlock profitable insights"
	subtitle="Everything you need to maximize your Vinted reselling profits with data-driven intelligence"
	features={[
		{
			title: "Real-time trend identification",
			description: "Spot emerging fashion trends and popular items before your competitors do. Get instant alerts when demand spikes to maximize your profit opportunities.",
			imageSrc: "/generated/image-a-diverse-group-of-people-in-a-modern-re.webp"
		},
		{
			title: "Competitive pricing intelligence",
			description: "Automatically analyze competitor pricing across thousands of listings. Price your items perfectly to sell fast while maximizing profit margins.",
			imageSrc: "/generated/image-a-team-of-professionals-in-a-bright-mini.webp"
		},
		{
			title: "Market opportunity discovery",
			description: "Discover untapped niches and high-demand categories with low competition. Find profitable items that other resellers are missing completely.",
			imageSrc: "/generated/image-a-group-of-business-professionals-in-a-w.webp"
		},
		{
			title: "Automated research engine",
			description: "Stop spending hours manually researching items and trends. Our AI analyzes millions of listings to deliver instant insights directly to you.",
			imageSrc: "/generated/image-researchers-in-a-tidy-sunlit-workspace-s.webp"
		},
		{
			title: "Profit optimization tools",
			description: "Calculate optimal listing times, seasonal demand patterns, and profit projections. Turn your side hustle into a predictable revenue stream.",
			imageSrc: "/generated/image-a-team-of-analysts-in-a-clean-organized-.webp"
		},
		{
			title: "Inventory performance tracking",
			description: "Track which items sell fastest and generate the highest profits. Focus your sourcing efforts on categories that consistently perform well.",
			imageSrc: "/generated/image-staff-in-a-well-arranged-stockroom-neatl.webp"
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />

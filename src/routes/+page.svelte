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
	centered={false}
	title="Ship features faster with zero coordination overhead"
	subtitle="Automated status updates and context sharing give your engineering team more time for deep work. Reclaim 15 hours per month from status meetings."
	imageSrc="/generated/image-a-software-engineer-sits-at-a-tidy-desk-.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Start 2-week pilot"
		},
		{
			href: "/about",
			label: "How it works"
		}
	]}
/>
<LogoScroller
	label="Trusted by high-performing engineering teams"
	logoUrls={[
		'https://cdn.brandfetch.io/vercel.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/supabase.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/resend.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/raycast.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Chandrasekaran",
			position: "Senior Software Engineer",
			company: "Basecamp",
			quote:
				"I reclaimed 12 hours per week that I used to spend in status meetings and writing updates. Now I actually have time to solve hard problems and ship features that matter.",
			image: "/generated/image-headshot-of-a-professional-asian-woman-w.webp"
		},
		{
			name: "Amir Rostami",
			position: "Engineering Lead",
			company: "Notion",
			quote:
				"Our team of 8 engineers saved $47,000 annually by eliminating coordination overhead. The 2-week pilot proved ROI immediately when our sprint velocity increased by 40%.",
			image: "/generated/image-headshot-of-a-professional-middle-easter.webp"
		},
		{
			name: "Keisha Thompson",
			position: "Staff Engineer",
			company: "Linear",
			quote:
				"I was skeptical about another tool, but this cut my context-switching by 60%. No more Slack interruptions asking for status updates. I finished our Q1 roadmap 3 weeks early.",
			image: "/generated/image-headshot-of-a-professional-black-woman-w.webp"
		}
	]}
/>

<Features
	title="Built for deep work, not coordination overhead"
	subtitle="Every feature is designed to eliminate interruptions and give your team more time for high-impact work"
	features={[
		{
			title: "Automated status updates",
			description:
				"Your work progress automatically surfaces to stakeholders without writing a single update. Eliminate 15+ hours of status meetings every month and stay in flow."
		},
		{
			title: "Instant context sharing",
			description:
				"Team members get the full context they need without interrupting you. No more Slack messages asking 'what's the status on this?'"
		},
		{
			title: "Deep work protection",
			description:
				"Your focus time is sacred and automatically protected from coordination requests. Reclaim 5+ hours weekly for the work that actually moves the needle."
		},
		{
			title: "Real-time sync",
			description:
				"Code commits, PR reviews, and deployment status sync automatically across your tools. Your team always has the latest information without manual updates."
		},
		{
			title: "Team visibility dashboard",
			description:
				"Engineering managers see progress across all projects at a glance. ICs ship features faster while leadership stays informed without status meetings."
		},
		{
			title: "Smart notification filters",
			description:
				"Only get interrupted for what truly matters. Intelligent filtering learns your priorities and eliminates notification noise that breaks your concentration."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Reclaim 5+ hours in your first week"
	subtitle="Risk-free 2-week pilot"
	description="Your team ships faster when coordination happens automatically. Start your pilot today and watch status meetings disappear while velocity increases. No commitment required."
	imageSrc="/generated/image-a-cheerful-software-engineer-sits-at-a-t.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Start 2-week pilot",
			variant: "primary"
		},
		{
			href: "/about",
			label: "See how it works",
			variant: "secondary"
		}
	]}
/>

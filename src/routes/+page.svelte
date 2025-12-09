<script>
  import Header from '$lib/components/Header.svelte';
  import Hero from '$lib/components/Hero.svelte';
  import FeaturesGrid from '$lib/components/FeaturesGrid.svelte';
  import AlternatingFeatures from '$lib/components/AlternatingFeatures.svelte';
  import TabsSection from '$lib/components/TabsSection.svelte';
  import CaseStudies from '$lib/components/CaseStudies.svelte';
  import ConnectSecurity from '$lib/components/ConnectSecurity.svelte';
  import DeveloperSection from '$lib/components/DeveloperSection.svelte';
  import BottomCTA from '$lib/components/BottomCTA.svelte';
  import Footer from '$lib/components/Footer.svelte';
</script>

<div class="min-h-screen bg-white font-sans antialiased">
  <Header />
  <main>
    <Hero />
    <FeaturesGrid />
    <AlternatingFeatures />
    <TabsSection />
    <CaseStudies />
    <ConnectSecurity />
    <DeveloperSection />
    <BottomCTA />
  </main>
  <Footer />
</div>


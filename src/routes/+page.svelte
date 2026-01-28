<script lang="ts">
  import Navbar from '$lib/components/Navbar.svelte';
  import Hero from '$lib/components/Hero.svelte';
  import ProblemStatement from '$lib/components/ProblemStatement.svelte';
  import FeaturesGrid from '$lib/components/FeaturesGrid.svelte';
  import Testimonials from '$lib/components/Testimonials.svelte';
  import CTA from '$lib/components/CTA.svelte';
  import Footer from '$lib/components/Footer.svelte';
</script>

<div class="min-h-screen bg-white font-body selection:bg-emerald-100 selection:text-emerald-900">
  <Navbar />
  
  <main>
    <Hero />
    <ProblemStatement />
    <FeaturesGrid />
    <Testimonials />
    <CTA />
  </main>

  <Footer />
</div>


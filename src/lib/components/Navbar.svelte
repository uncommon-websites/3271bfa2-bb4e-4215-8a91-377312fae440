<script lang="ts">
  import { onMount } from 'svelte';
  
  let isScrolled = $state(false);

  onMount(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 10;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<nav class={[
  'fixed top-0 left-0 right-0 z-50 transition-all duration-300',
  isScrolled ? 'bg-white/95 backdrop-blur-md border-b border-gray-200 py-3' : 'bg-white/80 backdrop-blur-sm py-5'
]}>
  <div class="container-custom flex items-center justify-between">
    <div class="flex items-center gap-8">
      <a href="/" class="flex items-center gap-3 text-xl font-bold tracking-tight text-gray-900">
        <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-emerald-600">
          <path d="M16 4L4 10V14C4 21.18 8.84 27.62 16 29C23.16 27.62 28 21.18 28 14V10L16 4Z" fill="currentColor" opacity="0.2"/>
          <path d="M16 4L4 10V14C4 21.18 8.84 27.62 16 29C23.16 27.62 28 21.18 28 14V10L16 4Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M12 16L15 19L20 13" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
        <span>Andrew Trower <span class="text-emerald-600">&</span> Associates</span>
      </a>
      
      <div class="hidden lg:flex items-center gap-8 text-sm font-medium text-gray-600">
        <a href="#services" class="hover:text-emerald-600 transition-colors">Services</a>
        <a href="#expertise" class="hover:text-emerald-600 transition-colors">Expertise</a>
        <a href="#results" class="hover:text-emerald-600 transition-colors">Results</a>
        <a href="#about" class="hover:text-emerald-600 transition-colors">About</a>
      </div>
    </div>

    <div class="flex items-center gap-3">
      <a href="#contact" class="px-5 py-2.5 text-sm font-semibold bg-emerald-600 text-white rounded-lg hover:bg-emerald-700 transition-colors">
        Schedule consultation
      </a>
    </div>
  </div>
</nav>

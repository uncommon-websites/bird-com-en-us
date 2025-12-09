<script>
  import Icon from './Icon.svelte';
</script>

<section class="py-20 px-6 max-w-7xl mx-auto">
  <div class="relative rounded-3xl overflow-hidden h-[500px] flex items-center">
    <!-- Background Image Placeholder -->
    <div class="absolute inset-0 bg-gray-900">
       <div class="w-full h-full bg-gradient-to-r from-black/80 to-transparent z-10 absolute inset-0"></div>
       <!-- Abstract pattern or image representation -->
       <div class="w-full h-full opacity-50 bg-[url('https://images.unsplash.com/photo-1522071820081-009f0129c71c?ixlib=rb-4.0.3&auto=format&fit=crop&w=2070&q=80')] bg-cover bg-center"></div>
    </div>

    <div class="relative z-20 px-12 md:px-16 max-w-3xl">
      <h2 class="text-4xl md:text-5xl font-bold text-white mb-8 leading-tight">
        The complete AI-native platform that scales with your business.
      </h2>
      <div class="flex gap-4">
        <button class="bg-blue-600 text-white px-6 py-3 rounded-full font-medium hover:bg-blue-700 transition-colors">
          Contact sales
        </button>
        <button class="bg-white text-gray-900 px-6 py-3 rounded-full font-medium hover:bg-gray-100 transition-colors">
          Start for free
        </button>
      </div>
    </div>
  </div>
</section>

<script>
  import Icon from './Icon.svelte';
</script>

<header class="w-full bg-white py-4 px-6 border-b border-transparent sticky top-0 z-50">
  <div class="max-w-7xl mx-auto flex items-center justify-between">
    <div class="flex items-center gap-8">
      <!-- Logo -->
      <a href="/" class="flex items-center gap-2">
        <div class="w-8 h-8 bg-black text-white flex items-center justify-center rounded-lg">
          <svg viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5">
             <path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z" fill="white"/>
          </svg>
        </div>
        <!-- <span class="font-bold text-xl tracking-tight">Bird</span> -->
      </a>

      <!-- Desktop Nav -->
      <nav class="hidden md:flex items-center gap-8">
        <a href="#" class="text-[15px] font-medium text-gray-600 hover:text-black">Product</a>
        <a href="#" class="text-[15px] font-medium text-gray-600 hover:text-black">Solutions</a>
        <a href="#" class="text-[15px] font-medium text-gray-600 hover:text-black">Resources</a>
        <a href="#" class="text-[15px] font-medium text-gray-600 hover:text-black">Company</a>
      </nav>
    </div>

    <!-- Right Actions -->
    <div class="flex items-center gap-4">
      <a href="#" class="text-[15px] font-medium text-gray-600 hover:text-black hidden md:block">Log in</a>
      <a href="#" class="bg-black text-white px-4 py-2 rounded-full text-[15px] font-medium hover:bg-gray-800 transition-colors">
        Contact sales
      </a>
      <button class="md:hidden text-gray-600">
        <Icon name="menu" className="w-6 h-6" />
      </button>
    </div>
  </div>
</header>

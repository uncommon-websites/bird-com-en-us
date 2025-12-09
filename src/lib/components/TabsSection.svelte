<script>
  import Icon from './Icon.svelte';
  
  let activeTab = 'Fintech and Finance';
  const tabs = ['Ecommerce and Retail', 'Fintech and Finance', 'SaaS'];
</script>

<section class="py-20 px-6 max-w-7xl mx-auto">
  <div class="flex flex-col md:flex-row justify-between items-start md:items-end mb-12 gap-6">
    <h2 class="text-4xl font-bold text-gray-900 max-w-2xl leading-tight">
      Businesses that turn customer data into intelligent experiences.
    </h2>
    <div class="flex gap-4">
      <button class="bg-blue-600 text-white px-6 py-3 rounded-full font-medium hover:bg-blue-700 transition-colors">
        Start for free
      </button>
      <button class="bg-white text-gray-900 border border-gray-200 px-6 py-3 rounded-full font-medium hover:bg-gray-50 transition-colors">
        Contact sales
      </button>
    </div>
  </div>

  <div class="border-b border-gray-200 mb-12">
    <div class="flex gap-8">
      {#each tabs as tab}
        <button 
          class="pb-4 text-sm font-medium transition-all relative {activeTab === tab ? 'text-blue-600' : 'text-gray-500 hover:text-gray-900'}"
          on:click={() => activeTab = tab}
        >
          {tab}
          {#if activeTab === tab}
            <div class="absolute bottom-0 left-0 w-full h-0.5 bg-blue-600"></div>
          {/if}
        </button>
      {/each}
    </div>
  </div>

  <!-- Content for Fintech and Finance -->
  <div class="bg-gray-50 rounded-2xl p-12 border border-gray-100 relative overflow-hidden min-h-[500px]">
    <!-- Background Flow Visualization -->
    <div class="absolute inset-0 flex items-center justify-center pointer-events-none opacity-50">
       <!-- Simplified flow representation -->
       <svg width="100%" height="100%" viewBox="0 0 800 400" preserveAspectRatio="none">
          <path d="M100 200 C 200 200, 300 100, 400 100 S 600 200, 700 200" fill="none" stroke="#e5e7eb" stroke-width="2" stroke-dasharray="4 4"/>
       </svg>
    </div>

    <div class="relative z-10 flex flex-col items-center justify-center h-full gap-8">
       <div class="text-pink-500 text-xs font-medium bg-white px-3 py-1 rounded-full shadow-sm border border-pink-100 mb-4">
          Previously: abandons at biometric step
       </div>
       
       <div class="bg-white p-6 rounded-2xl shadow-xl border border-gray-100 max-w-md w-full text-center relative">
          <div class="absolute -top-12 left-1/2 -translate-x-1/2 text-xs text-gray-400 w-full text-center">
             High drop-off risk: 78%
          </div>
          
          <!-- Red overlay box -->
          <div class="bg-red-100/50 rounded-xl p-8 mb-4 border border-red-100 flex items-center justify-center h-32">
             <span class="text-red-400 font-medium">Verification incomplete</span>
          </div>
          
          <div class="flex justify-between text-xs text-gray-400 mt-4">
             <span>Avg completion time: &lt; 2m</span>
             <span>Success rate: 89% | Email 42%</span>
          </div>
       </div>

       <div class="flex items-center gap-2 mt-8">
          <div class="w-8 h-8 rounded-full bg-gray-200 overflow-hidden border-2 border-white shadow-sm">
             <!-- Avatar placeholder -->
             <svg class="w-full h-full text-gray-400" fill="currentColor" viewBox="0 0 24 24"><path d="M24 24H0V0h24v24z" fill="none"/><path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z"/></svg>
          </div>
          <div class="text-xs text-gray-500">Organic search: 'margin trading platform'</div>
       </div>
    </div>
  </div>

  <div class="mt-8 flex justify-between items-center">
    <div class="flex items-baseline gap-2">
      <span class="text-5xl font-bold text-blue-600">67%</span>
      <span class="text-gray-900 font-medium max-w-md">Faster user activation <span class="text-gray-500 font-normal">through intelligent onboarding and verification flows.</span></span>
    </div>
    <a href="#" class="text-blue-600 font-medium flex items-center gap-1 hover:gap-2 transition-all">
      Fintech and Finance solutions <Icon name="arrow-right" className="w-4 h-4" />
    </a>
  </div>
</section>

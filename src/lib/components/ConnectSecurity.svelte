<script>
  import Icon from './Icon.svelte';
</script>

<section class="py-20 px-6 max-w-7xl mx-auto">
  <div class="grid grid-cols-1 md:grid-cols-2 gap-16">
    <!-- Left Column: Connect Anywhere -->
    <div>
      <h3 class="text-2xl font-bold text-gray-900 mb-2">Connect anywhere</h3>
      <p class="text-gray-600 mb-6">Plug in and get started immediately.</p>
      <a href="#" class="text-blue-600 font-medium flex items-center gap-1 hover:gap-2 transition-all mb-8">
        Integrations <Icon name="arrow-right" className="w-4 h-4" />
      </a>
      
      <div class="bg-gray-50 rounded-2xl p-8 h-64 flex items-center justify-center mb-8">
         <div class="flex gap-6 items-center grayscale opacity-70">
            <!-- Logos placeholder -->
            <div class="w-12 h-12 bg-green-500 rounded"></div>
            <div class="w-12 h-12 bg-blue-400 rounded-full"></div>
            <div class="w-12 h-12 bg-orange-500 rounded-full"></div>
            <div class="w-12 h-12 bg-blue-300 rounded-full"></div>
         </div>
      </div>

      <div class="grid grid-cols-2 gap-8">
        <div>
           <div class="flex items-center gap-2 mb-2 text-gray-900 font-semibold text-sm">
              <Icon name="check" className="w-4 h-4 text-gray-900" /> Go live in minutes
           </div>
           <p class="text-xs text-gray-500 leading-relaxed">Pre-built connectors for every major platform.</p>
        </div>
        <div>
           <div class="flex items-center gap-2 mb-2 text-gray-900 font-semibold text-sm">
              <Icon name="check" className="w-4 h-4 text-gray-900" /> Complete data picture
           </div>
           <p class="text-xs text-gray-500 leading-relaxed">Pull from every source, push to every system.</p>
        </div>
      </div>
    </div>

    <!-- Right Column: Enterprise-level security -->
    <div>
      <h3 class="text-2xl font-bold text-gray-900 mb-2">Enterprise-level security.</h3>
      <p class="text-gray-600 mb-6">Keep your data private.</p>
      <a href="#" class="text-blue-600 font-medium flex items-center gap-1 hover:gap-2 transition-all mb-8">
        Security & Compliance <Icon name="arrow-right" className="w-4 h-4" />
      </a>
      
      <div class="bg-gray-50 rounded-2xl p-8 h-64 flex items-center justify-center mb-8">
         <div class="flex gap-6 items-center opacity-40">
            <span class="font-bold text-xl">SOC2</span>
            <span class="font-bold text-xl">SSO</span>
            <span class="font-bold text-xl">OKTA</span>
            <span class="font-bold text-xl">ISO</span>
         </div>
      </div>

      <div class="grid grid-cols-2 gap-8">
        <div>
           <div class="flex items-center gap-2 mb-2 text-gray-900 font-semibold text-sm">
              <Icon name="check" className="w-4 h-4 text-gray-900" /> Enterprise data security
           </div>
           <p class="text-xs text-gray-500 leading-relaxed">Encryption, granular access control, build for AI systems.</p>
        </div>
        <div>
           <div class="flex items-center gap-2 mb-2 text-gray-900 font-semibold text-sm">
              <Icon name="check" className="w-4 h-4 text-gray-900" /> Certified compliance
           </div>
           <p class="text-xs text-gray-500 leading-relaxed">Meet the highest global standards for AI and data processing.</p>
        </div>
      </div>
    </div>
  </div>
</section>

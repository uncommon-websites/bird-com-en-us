<script>
  import Icon from './Icon.svelte';
</script>

<section class="py-20 px-6 max-w-7xl mx-auto">
  <div class="mb-12">
    <h2 class="text-3xl font-bold text-gray-900 mb-2">Trusted by companies that depend on their data.</h2>
    <p class="text-xl text-gray-600 mb-6">See how leading brands use Bird CDP to drive intelligent marketing.</p>
    <a href="#" class="text-blue-600 font-medium flex items-center gap-1 hover:gap-2 transition-all">
      View all customer stories <Icon name="arrow-right" className="w-4 h-4" />
    </a>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-16">
    <!-- Card 1: Airwallex -->
    <div class="group relative h-[400px] rounded-2xl overflow-hidden cursor-pointer">
      <div class="absolute inset-0 bg-gray-900">
         <!-- Placeholder Image -->
         <div class="w-full h-full bg-gradient-to-br from-blue-900 to-black opacity-60 mix-blend-multiply"></div>
      </div>
      <div class="absolute inset-0 p-8 flex flex-col justify-between">
        <div class="text-white font-bold text-xl flex items-center gap-2">
           <!-- Airwallex Logo -->
           <div class="w-6 h-6 bg-white/20 rounded-sm"></div> Airwallex
        </div>
        <div>
          <div class="text-5xl font-bold text-white mb-2">94.4%</div>
          <div class="text-white/80 text-sm">SMS deliverability improved</div>
        </div>
      </div>
    </div>

    <!-- Card 2: Glovo -->
    <div class="group relative h-[400px] rounded-2xl overflow-hidden cursor-pointer">
      <div class="absolute inset-0 bg-gray-900">
         <!-- Placeholder Image -->
         <div class="w-full h-full bg-gradient-to-br from-yellow-900 to-black opacity-60 mix-blend-multiply"></div>
      </div>
      <div class="absolute inset-0 p-8 flex flex-col justify-between">
        <div class="text-white font-bold text-xl flex items-center gap-2">
           <!-- Glovo Logo -->
           <div class="w-6 h-6 bg-yellow-500 rounded-full"></div> Glovo
        </div>
        <div>
          <div class="text-5xl font-bold text-white mb-2">+300%</div>
          <div class="text-white/80 text-sm">Partner onboarding efficiency</div>
        </div>
      </div>
    </div>

    <!-- Card 3: Zillow -->
    <div class="group relative h-[400px] rounded-2xl overflow-hidden cursor-pointer">
      <div class="absolute inset-0 bg-gray-900">
         <!-- Placeholder Image -->
         <div class="w-full h-full bg-gradient-to-br from-blue-800 to-black opacity-60 mix-blend-multiply"></div>
      </div>
      <div class="absolute inset-0 p-8 flex flex-col justify-between">
        <div class="text-white font-bold text-xl flex items-center gap-2">
           <!-- Zillow Logo -->
           <div class="w-6 h-6 bg-blue-500 rounded-sm"></div> Zillow
        </div>
        <div>
          <div class="text-5xl font-bold text-white mb-2">161%</div>
          <div class="text-white/80 text-sm">Open rate improvement</div>
        </div>
      </div>
    </div>
  </div>

  <!-- Logos Strip -->
  <div class="border-t border-gray-200 pt-12">
    <div class="flex flex-wrap justify-between items-center gap-8 opacity-60 grayscale">
       <div class="text-xs font-medium text-gray-500 max-w-[150px]">Fortune 500 companies that depend on Bird</div>
       <div class="h-6 flex items-center font-bold text-xl gap-1"><div class="w-5 h-5 rounded-full bg-red-600 text-white flex items-center justify-center text-xs font-serif">P</div> Pinterest</div>
       <div class="h-6 flex items-center font-bold text-xl tracking-tighter">Uber</div>
       <div class="h-6 flex items-center font-bold text-xl italic">PayPal</div>
       <div class="h-6 flex items-center font-bold text-xl gap-1"><div class="w-5 h-5 rounded-full border border-current flex items-center justify-center text-[10px]">∞</div> Meta</div>
       <div class="h-6 flex items-center font-bold text-xl gap-1"><div class="w-5 h-5 bg-red-600 text-white font-bold flex items-center justify-center text-[10px]">A</div> Adobe</div>
    </div>
  </div>
</section>

<script>
  import Icon from './Icon.svelte';
</script>

<section class="pt-16 pb-12 px-6 max-w-7xl mx-auto">
  <div class="max-w-3xl">
    <h1 class="text-6xl font-bold tracking-tight text-gray-900 leading-[1.1] mb-6">
      Marketing built <span class="text-green-600">for<br>the AI era.</span>
    </h1>
    <p class="text-xl text-gray-600 mb-8 max-w-2xl leading-relaxed">
      The complete platform for enterprise brands to acquire, convert, and retain customers across every channel—powered by AI that actually understands your business.
    </p>
    <div class="flex flex-wrap gap-3 mb-16">
      <button class="bg-blue-600 text-white px-6 py-3 rounded-full font-medium hover:bg-blue-700 transition-colors">
        Contact sales
      </button>
      <button class="bg-white text-gray-900 border border-gray-200 px-6 py-3 rounded-full font-medium hover:bg-gray-50 transition-colors">
        Start for free
      </button>
    </div>
  </div>

  <!-- Logos Section -->
  <div class="mb-12">
    <p class="text-xs font-medium text-gray-500 mb-6 uppercase tracking-wide">Fortune 500 companies that depend on Bird</p>
    <div class="flex flex-wrap items-center gap-8 opacity-70 grayscale">
       <!-- Pinterest -->
       <div class="h-6 flex items-center"><span class="font-bold text-xl flex items-center gap-1"><div class="w-5 h-5 rounded-full bg-red-600 text-white flex items-center justify-center text-xs font-serif">P</div> Pinterest</span></div>
       <!-- Uber -->
       <div class="h-6 flex items-center"><span class="font-bold text-xl tracking-tighter">Uber</span></div>
       <!-- Square -->
       <div class="h-6 flex items-center"><span class="font-bold text-xl flex items-center gap-1"><div class="w-5 h-5 border-2 border-black rounded-sm"></div> Square</span></div>
       <!-- Airwallex -->
       <div class="h-6 flex items-center"><span class="font-bold text-xl flex items-center gap-1">Airwallex</span></div>
       <!-- Adobe -->
       <div class="h-6 flex items-center"><span class="font-bold text-xl flex items-center gap-1"><div class="w-5 h-5 bg-red-600 text-white font-bold flex items-center justify-center text-[10px]">A</div> Adobe</span></div>
    </div>
  </div>

  <!-- Hero Image / Dashboard Mockup -->
  <div class="relative w-full rounded-2xl overflow-hidden shadow-2xl border border-gray-200 bg-gray-50 aspect-[16/9] group">
    <!-- Mockup Content -->
    <div class="absolute inset-0 p-8 flex flex-col">
       <!-- Flowchart nodes simulation -->
       <div class="w-full h-full relative">
          <!-- Central line -->
          <div class="absolute top-0 bottom-0 left-1/2 w-0.5 bg-gray-200 -translate-x-1/2"></div>
          
          <!-- Node 1: Wait -->
          <div class="absolute top-[10%] left-1/2 -translate-x-1/2 bg-white p-3 rounded-lg shadow-sm border border-gray-200 flex items-center gap-3 w-64 z-10">
            <div class="w-8 h-8 rounded bg-orange-100 flex items-center justify-center text-orange-600">
               <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><path d="M12 6v6l4 2"/></svg>
            </div>
            <div>
               <div class="text-sm font-semibold text-gray-900">Wait</div>
               <div class="text-xs text-gray-500">Continue in 1 day at 12:00 PM</div>
            </div>
          </div>

          <!-- Node 2: Condition -->
          <div class="absolute top-[35%] left-1/2 -translate-x-1/2 bg-white p-3 rounded-lg shadow-sm border border-gray-200 flex items-center gap-3 w-64 z-10">
            <div class="w-8 h-8 rounded bg-pink-100 flex items-center justify-center text-pink-600">
               <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M4 4h16v16H4z"/><path d="M12 4v16"/><path d="M4 12h16"/></svg>
            </div>
            <div>
               <div class="text-sm font-semibold text-gray-900">Condition</div>
               <div class="text-xs text-gray-500">Check for details and subscription</div>
            </div>
          </div>

          <!-- Branching lines -->
          <svg class="absolute top-[35%] left-1/2 -translate-x-1/2" width="302" height="100" style="overflow: visible; pointer-events: none;">
             <!-- Center is 151. Left is 1. Right is 301. -->
             <path d="M151 0 v25 h-150 v55" fill="none" stroke="#e5e7eb" stroke-width="2" />
             <path d="M151 0 v25 h150 v55" fill="none" stroke="#e5e7eb" stroke-width="2" />
          </svg>

          <!-- Node 3 Left: Send a message (WhatsApp) -->
          <div class="absolute top-[60%] left-[calc(50%-150px)] -translate-x-1/2 bg-white p-3 rounded-lg shadow-sm border border-gray-200 flex items-center gap-3 w-64 z-10">
            <div class="w-8 h-8 rounded bg-green-100 flex items-center justify-center text-green-600">
               <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.008-.57-.008-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
            </div>
            <div>
               <div class="text-sm font-semibold text-gray-900">Send a message</div>
               <div class="text-xs text-gray-500">WhatsApp</div>
            </div>
          </div>

          <!-- Node 3 Right: Send a message (Email) -->
          <div class="absolute top-[60%] left-[calc(50%+150px)] -translate-x-1/2 bg-white p-3 rounded-lg shadow-sm border border-gray-200 flex items-center gap-3 w-64 z-10">
            <div class="w-8 h-8 rounded bg-blue-100 flex items-center justify-center text-blue-600">
               <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"/></svg>
            </div>
            <div>
               <div class="text-sm font-semibold text-gray-900">Send a message</div>
               <div class="text-xs text-gray-500">Email</div>
            </div>
          </div>
       </div>
    </div>
  </div>
</section>

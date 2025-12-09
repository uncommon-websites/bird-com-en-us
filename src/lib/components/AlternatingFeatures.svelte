<script>
  import Icon from './Icon.svelte';
</script>

<section class="py-20 px-6 max-w-7xl mx-auto">
  <div class="max-w-3xl mb-24">
    <h2 class="text-5xl font-bold text-gray-900 mb-6 leading-tight">Turn scattered customer data into revenue growth.</h2>
    <p class="text-xl text-gray-600 mb-8 leading-relaxed">
      Every interaction feeds into a unified customer view that powers personalized experiences, targeted campaigns, and intelligent automation across every touchpoint.
    </p>
    <div class="flex gap-4">
      <button class="bg-blue-600 text-white px-6 py-3 rounded-full font-medium hover:bg-blue-700 transition-colors">
        Start for free
      </button>
      <button class="bg-white text-gray-900 border border-gray-200 px-6 py-3 rounded-full font-medium hover:bg-gray-50 transition-colors">
        Contact sales
      </button>
    </div>
  </div>

  <!-- Feature 1: Transform visitors -->
  <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center mb-32">
    <div>
      <h3 class="text-3xl font-bold text-gray-900 mb-4">Transform visitors<br>into lifetime customers.</h3>
      <p class="text-lg text-gray-600 mb-8 leading-relaxed">
        AI-powered journeys that adapt to each customer's behavior. From first click to loyal advocate, Bird orchestrates every touchpoint for maximum impact.
      </p>
      <a href="#" class="text-blue-600 font-medium flex items-center gap-1 hover:gap-2 transition-all">
        Marketing platform <Icon name="arrow-right" className="w-4 h-4" />
      </a>
    </div>
    <div class="bg-gray-50 rounded-2xl p-8 border border-gray-100 shadow-lg">
      <!-- Mockup of Workflow -->
      <div class="flex flex-col items-center gap-6">
         <div class="bg-white p-4 rounded-xl shadow-sm border border-gray-200 w-64 text-center">
            <div class="flex items-center justify-center w-8 h-8 bg-purple-100 text-purple-600 rounded-lg mx-auto mb-2">
               <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"/></svg>
            </div>
            <div class="font-semibold text-sm">Condition</div>
            <div class="text-xs text-gray-500">Book a demo form completed</div>
         </div>
         
         <div class="flex gap-8 w-full justify-center relative max-w-[480px] mx-auto">
            <!-- Connecting lines -->
            <svg class="absolute -top-6 left-0 w-full h-6" style="overflow: visible">
               <!-- Center is 240. Left node center is ~112. Right node center is ~368. -->
               <path d="M240 0 L240 10 L112 10 L112 24" fill="none" stroke="#e5e7eb" stroke-width="2" />
               <path d="M240 0 L240 10 L368 10 L368 24" fill="none" stroke="#e5e7eb" stroke-width="2" />
            </svg>

            <div class="bg-white p-4 rounded-xl shadow-sm border border-gray-200 w-56">
               <div class="flex items-center gap-2 mb-2">
                  <div class="w-6 h-6 bg-orange-100 text-orange-600 rounded flex items-center justify-center">
                     <svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M4 4h16v16H4z"/></svg>
                  </div>
                  <span class="font-semibold text-sm">Update record</span>
               </div>
               <div class="text-xs text-gray-500">Update Sales pipeline list</div>
            </div>

            <div class="bg-white p-4 rounded-xl shadow-sm border border-gray-200 w-56">
               <div class="flex items-center gap-2 mb-2">
                  <div class="w-6 h-6 bg-green-100 text-green-600 rounded flex items-center justify-center">
                     <svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg>
                  </div>
                  <span class="font-semibold text-sm">Send SMS</span>
               </div>
               <div class="flex items-center gap-2 text-xs text-gray-500">
                  <div class="flex -space-x-1">
                     <div class="w-4 h-4 rounded-full bg-gray-300 border border-white"></div>
                     <div class="w-4 h-4 rounded-full bg-gray-400 border border-white"></div>
                  </div>
                  141 recipients
               </div>
               <div class="mt-2 text-[10px] bg-pink-50 text-pink-600 px-2 py-1 rounded-full inline-block">
                  ✨ Generating message
               </div>
            </div>
         </div>
      </div>
    </div>
  </div>

  <!-- Feature 2: Make all your data actionable -->
  <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center mb-32">
    <div class="bg-gray-50 rounded-2xl p-8 border border-gray-100 shadow-lg order-2 lg:order-1">
       <!-- Data List Mockup -->
       <div class="space-y-3">
          <div class="bg-white p-4 rounded-xl shadow-sm border border-gray-200 flex items-center justify-between">
             <div class="flex items-center gap-3">
                <div class="w-8 h-8 bg-green-100 text-green-600 rounded-lg flex items-center justify-center">
                   <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M6 2L3 6v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V6l-3-4z"/><line x1="3" y1="6" x2="21" y2="6"/><path d="M16 10a4 4 0 0 1-8 0"/></svg>
                </div>
                <span class="font-medium text-sm">Cart abandonment spike</span>
             </div>
             <div class="text-gray-400">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg>
             </div>
          </div>
          <div class="bg-white p-4 rounded-xl shadow-sm border border-gray-200 flex items-center justify-between">
             <div class="flex items-center gap-3">
                <div class="w-8 h-8 bg-blue-100 text-blue-600 rounded-lg flex items-center justify-center">
                   <span class="font-bold text-xs">$</span>
                </div>
                <span class="font-medium text-sm">$84K left in 312 carts today</span>
             </div>
             <div class="text-gray-400">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg>
             </div>
          </div>
          <div class="bg-white p-4 rounded-xl shadow-sm border border-gray-200 flex items-center justify-between">
             <div class="flex items-center gap-3">
                <div class="w-8 h-8 bg-purple-100 text-purple-600 rounded-lg flex items-center justify-center">
                   <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/></svg>
                </div>
                <span class="font-medium text-sm">45 Opportunities closing this...</span>
             </div>
             <div class="text-gray-400">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg>
             </div>
          </div>
          <div class="bg-white p-4 rounded-xl shadow-sm border border-pink-200 flex items-center justify-between ring-2 ring-pink-100">
             <div class="flex items-center gap-3">
                <div class="w-8 h-8 bg-pink-100 text-pink-600 rounded-lg flex items-center justify-center">
                   <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M12 2v4M12 18v4M4.93 4.93l2.83 2.83M16.24 16.24l2.83 2.83M2 12h4M18 12h4M4.93 19.07l2.83-2.83M16.24 7.76l2.83-2.83"/></svg>
                </div>
                <span class="font-medium text-sm">Detected 128 new records...</span>
                <span class="bg-pink-100 text-pink-600 text-[10px] px-2 py-0.5 rounded-full font-medium">Processing</span>
             </div>
          </div>
       </div>
    </div>
    <div class="order-1 lg:order-2">
      <h3 class="text-3xl font-bold text-gray-900 mb-4">Make all your data<br>instantly actionable.</h3>
      <p class="text-lg text-gray-600 mb-8 leading-relaxed">
        Connect every data source into one intelligent platform. Create custom objects, model complex relationships, and build segments that drive better marketing decisions.
      </p>
      <a href="#" class="text-blue-600 font-medium flex items-center gap-1 hover:gap-2 transition-all">
        Data platform <Icon name="arrow-right" className="w-4 h-4" />
      </a>
    </div>
  </div>
  
  <!-- Feature 3: Let AI handle the repetitive work -->
  <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center mb-32">
    <div>
      <h3 class="text-3xl font-bold text-gray-900 mb-4">Let AI handle the<br>repetitive work.</h3>
      <p class="text-lg text-gray-600 mb-8 leading-relaxed">
        Set up campaigns once and let Bird's automation optimize, personalize, and improve them continuously. Your marketing runs itself while you focus on growth.
      </p>
      <a href="#" class="text-blue-600 font-medium flex items-center gap-1 hover:gap-2 transition-all">
        Marketing automation <Icon name="arrow-right" className="w-4 h-4" />
      </a>
    </div>
    <div class="bg-gray-50 rounded-2xl p-8 border border-gray-100 shadow-lg relative overflow-hidden h-80 flex items-center justify-center">
       <!-- AI Tags Cloud -->
       <div class="flex flex-wrap gap-4 justify-center content-center max-w-sm">
          <div class="bg-pink-100 text-pink-600 px-4 py-2 rounded-full flex items-center gap-2 text-sm font-medium shadow-sm">
             <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M21 12a9 9 0 1 1-6.219-8.56"/></svg>
             Optimizing delivery route
          </div>
          <div class="bg-pink-100 text-pink-600 px-4 py-2 rounded-full flex items-center gap-2 text-sm font-medium shadow-sm">
             <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="m12 19-7-7 7-7"/><path d="M19 12H5"/></svg>
             Suggested subject
          </div>
          <div class="bg-pink-100 text-pink-600 px-4 py-2 rounded-full flex items-center gap-2 text-sm font-medium shadow-sm">
             Generating headline
          </div>
          <div class="bg-pink-100 text-pink-600 px-4 py-2 rounded-full flex items-center gap-2 text-sm font-medium shadow-sm">
             <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="m5 8 6 6"/><path d="m4 14 6-6 2-3"/><path d="M2 5h12"/><path d="M7 2h1"/></svg>
             Translating
          </div>
          <div class="bg-pink-100 text-pink-600 px-4 py-2 rounded-full flex items-center gap-2 text-sm font-medium shadow-sm">
             <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M12 2v4M12 18v4M4.93 4.93l2.83 2.83M16.24 16.24l2.83 2.83M2 12h4M18 12h4M4.93 19.07l2.83-2.83M16.24 7.76l2.83-2.83"/></svg>
             Building segments
          </div>
          <div class="bg-pink-100 text-pink-600 px-4 py-2 rounded-full flex items-center gap-2 text-sm font-medium shadow-sm">
             Detecting sentiment
          </div>
          <div class="bg-pink-100 text-pink-600 px-4 py-2 rounded-full flex items-center gap-2 text-sm font-medium shadow-sm">
             <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M11 4H4a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-7"/><path d="M18.5 2.5a2.121 2.121 0 0 1 3 3L12 15l-4 1 1-4 9.5-9.5z"/></svg>
             Updating journey conditions
          </div>
       </div>
    </div>
  </div>

  <!-- Feature 4: Own your customer communication -->
  <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
    <div class="bg-gray-50 rounded-2xl p-8 border border-gray-100 shadow-lg order-2 lg:order-1 h-80 flex items-center justify-center">
       <!-- Icons Grid -->
       <div class="grid grid-cols-4 gap-4">
          <div class="w-14 h-14 bg-white rounded-xl shadow-sm flex items-center justify-center text-blue-500"><svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C5.373 0 0 5.373 0 12s5.373 12 12 12 12-5.373 12-12S18.627 0 12 0zm5.562 8.161c-.18 1.897-.962 6.502-1.359 8.627-.168.9-.5 1.201-.82 1.23-.697.064-1.226-.461-1.901-.903-1.056-.693-1.653-1.124-2.678-1.8-1.185-.78-.417-1.21.258-1.91.177-.184 3.247-2.977 3.307-3.23.007-.032.014-.15-.056-.212s-.174-.041-.249-.024c-.106.024-1.793 1.14-5.061 3.345-.48.33-.913.49-1.302.48-.428-.008-1.252-.241-1.865-.44-.752-.245-1.349-.374-1.297-.789.027-.216.325-.437.893-.663 3.498-1.524 5.83-2.529 6.998-3.014 3.332-1.386 4.025-1.627 4.476-1.635.099-.002.321.023.465.141.119.098.152.228.166.33.016.114.032.333.015.534z"/></svg></div>
          <div class="w-14 h-14 bg-white rounded-xl shadow-sm flex items-center justify-center text-purple-500"><svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 15h-2v-6h2v6zm-1-7c-.55 0-1-.45-1-1s.45-1 1-1 1 .45 1 1-.45 1-1 1zm5 7h-2v-6h2v6z"/></svg></div>
          <div class="w-14 h-14 bg-white rounded-xl shadow-sm flex items-center justify-center text-blue-600"><svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2C6.477 2 2 6.145 2 11.258c0 2.85 1.396 5.408 3.633 7.075V22l3.33-1.828c1.558.432 3.204.686 4.937.686 5.523 0 10-4.145 10-9.258C24 6.145 19.523 2 12 2z"/></svg></div>
          <div class="w-14 h-14 bg-white rounded-xl shadow-sm flex items-center justify-center text-pink-500"><svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.069-4.85.069-3.204 0-3.584-.012-4.849-.069-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg></div>
          <div class="w-14 h-14 bg-white rounded-xl shadow-sm flex items-center justify-center text-blue-400"><svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 15h-2v-6h2v6zm-1-7c-.55 0-1-.45-1-1s.45-1 1-1 1 .45 1 1-.45 1-1 1zm5 7h-2v-6h2v6z"/></svg></div>
          <div class="w-14 h-14 bg-white rounded-xl shadow-sm flex items-center justify-center text-purple-600"><svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24"><path d="M21 16.5c0 .38-.21.71-.53.88l-7.9 4.44c-.16.12-.36.18-.57.18-.21 0-.41-.06-.57-.18l-7.9-4.44A.991.991 0 0 1 3 16.5v-9c0-.38.21-.71.53-.88l7.9-4.44c.16-.12.36-.18.57-.18.21 0 .41.06.57.18l7.9 4.44c.32.17.53.5.53.88v9zM12 4.15 6.04 7.5 12 10.85l5.96-3.35L12 4.15zM5 15.91l6 3.38v-6.71L5 9.21v6.7zM13 12.58v6.71l6-3.38v-6.7l-6 3.37z"/></svg></div>
          <div class="w-14 h-14 bg-white rounded-xl shadow-sm flex items-center justify-center text-green-500"><svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24"><path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.174.2-.297.3-.496.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.501-.669-.51l-.57-.008c-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.626.712.226 1.36.194 1.872.118.571-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"/></svg></div>
          <div class="w-14 h-14 bg-white rounded-xl shadow-sm flex items-center justify-center text-blue-600"><svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4-8 5-8-5V6l8 5 8-5v2z"/></svg></div>
       </div>
    </div>
    <div class="order-1 lg:order-2">
      <h3 class="text-3xl font-bold text-gray-900 mb-4">Own your customer<br>communication.</h3>
      <p class="text-lg text-gray-600 mb-8 leading-relaxed">
        Reach customers on email, SMS, WhatsApp, and beyond with infrastructure built for enterprise scale and deliverability that actually works.
      </p>
      <a href="#" class="text-blue-600 font-medium flex items-center gap-1 hover:gap-2 transition-all">
        Communication channels <Icon name="arrow-right" className="w-4 h-4" />
      </a>
    </div>
  </div>
</section>

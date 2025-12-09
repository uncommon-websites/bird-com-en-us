<script>
  import Icon from './Icon.svelte';
</script>

<section class="py-20 px-6 max-w-7xl mx-auto">
  <div class="bg-blue-600 rounded-3xl p-12 md:p-16 text-white relative overflow-hidden">
    <!-- Background decorative elements -->
    <div class="absolute top-0 right-0 w-1/2 h-full opacity-10 pointer-events-none">
       <div class="grid grid-cols-12 gap-2 h-full">
          {#each Array(100) as _}
             <div class="w-1 h-1 bg-white rounded-full"></div>
          {/each}
       </div>
    </div>

    <div class="relative z-10">
      <div class="text-xs font-bold tracking-widest uppercase mb-6 opacity-80">Development</div>
      <h2 class="text-4xl md:text-5xl font-bold mb-6 max-w-2xl leading-tight">
        Enterprise-ready APIs for developers who want to build custom experiences.
      </h2>
      
      <div class="flex gap-4 mb-12">
        <button class="bg-white text-blue-600 px-6 py-3 rounded-full font-medium hover:bg-blue-50 transition-colors">
          Contact sales
        </button>
        <button class="bg-transparent border border-white/30 text-white px-6 py-3 rounded-full font-medium hover:bg-white/10 transition-colors">
          Start for free
        </button>
      </div>

      <p class="text-lg text-blue-100 mb-16 max-w-2xl leading-relaxed">
        For teams that need direct programmatic access, Bird also offers comprehensive APIs that power messaging infrastructure for thousands of companies worldwide.
      </p>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Card 1 -->
        <div class="bg-blue-500/20 backdrop-blur-sm border border-white/10 rounded-2xl p-8 hover:bg-blue-500/30 transition-colors">
           <div class="w-10 h-10 bg-white rounded-lg flex items-center justify-center text-blue-600 mb-6">
              <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4-8 5-8-5V6l8 5 8-5v2z"/></svg>
           </div>
           <h3 class="text-xl font-bold mb-2">SMS API</h3>
           <p class="text-sm text-blue-100 mb-6 leading-relaxed">Global SMS delivery with &lt;2.5 second delivery for 95% of messages. Local numbers in 140+ countries, with automatic failover.</p>
           <a href="#" class="text-white font-medium text-sm flex items-center gap-1 hover:gap-2 transition-all">
             Learn more <Icon name="arrow-right" className="w-3 h-3" />
           </a>
        </div>

        <!-- Card 2 -->
        <div class="bg-blue-500/20 backdrop-blur-sm border border-white/10 rounded-2xl p-8 hover:bg-blue-500/30 transition-colors">
           <div class="w-10 h-10 bg-white rounded-lg flex items-center justify-center text-blue-600 mb-6">
              <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 14H4V8l8 5 8-5v10zm-8-7L4 6h16l-8 5z"/></svg>
           </div>
           <h3 class="text-xl font-bold mb-2">Email API</h3>
           <p class="text-sm text-blue-100 mb-6 leading-relaxed">Own and operate the channels: 40% of world's email and SMS with 99.95% SLA-backed uptime.</p>
           <a href="#" class="text-white font-medium text-sm flex items-center gap-1 hover:gap-2 transition-all">
             Learn more <Icon name="arrow-right" className="w-3 h-3" />
           </a>
        </div>

        <!-- Card 3 -->
        <div class="bg-blue-500/20 backdrop-blur-sm border border-white/10 rounded-2xl p-8 hover:bg-blue-500/30 transition-colors">
           <div class="w-10 h-10 bg-white rounded-lg flex items-center justify-center text-blue-600 mb-6">
              <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M20 15.5c-1.25 0-2.45-.2-3.57-.57-.35-.11-.74-.03-1.02.24l-2.2 2.2a15.045 15.045 0 0 1-6.59-6.59l2.2-2.21c.28-.26.36-.65.25-1.02A11.36 11.36 0 0 1 8.5 4c0-.55-.45-1-1-1H4c-.55 0-1 .45-1 1 0 9.39 7.61 17 17 17 .55 0 1-.45 1-1v-3.5c0-.55-.45-1-1-1zM19 12h2a9 9 0 0 0-9-9v2c3.87 0 7 3.13 7 7zm-4 0h2c0-1.66-1.34-3-3-3v2c.55 0 1 .45 1 1z"/></svg>
           </div>
           <h3 class="text-xl font-bold mb-2">Voice API</h3>
           <p class="text-sm text-blue-100 mb-6 leading-relaxed">Two-way voice calling with global coverage. Perfect for authentication, notifications, and customer engagement.</p>
           <a href="#" class="text-white font-medium text-sm flex items-center gap-1 hover:gap-2 transition-all">
             Learn more <Icon name="arrow-right" className="w-3 h-3" />
           </a>
        </div>

        <!-- Card 4 -->
        <div class="bg-blue-500/20 backdrop-blur-sm border border-white/10 rounded-2xl p-8 hover:bg-blue-500/30 transition-colors">
           <div class="w-10 h-10 bg-white rounded-lg flex items-center justify-center text-green-500 mb-6">
              <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.174.2-.297.3-.496.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.501-.669-.51l-.57-.008c-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.626.712.226 1.36.194 1.872.118.571-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"/></svg>
           </div>
           <h3 class="text-xl font-bold mb-2">WhatsApp Business API</h3>
           <p class="text-sm text-blue-100 mb-6 leading-relaxed">Send rich media messages with AI-optimized timing. Perfect for AI-triggered customer service and personalized engagement.</p>
           <a href="#" class="text-white font-medium text-sm flex items-center gap-1 hover:gap-2 transition-all">
             Learn more <Icon name="arrow-right" className="w-3 h-3" />
           </a>
        </div>

        <!-- Card 5 -->
        <div class="bg-blue-500/20 backdrop-blur-sm border border-white/10 rounded-2xl p-8 hover:bg-blue-500/30 transition-colors">
           <div class="w-10 h-10 bg-white rounded-lg flex items-center justify-center text-blue-600 mb-6">
              <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2L2 7l10 5 10-5-10-5zm0 9l2.5-1.25L12 8.5l-2.5 1.25L12 11zm0 2.5l-5-2.5-5 2.5L12 22l10-8.5-5-2.5-5 2.5z"/></svg>
           </div>
           <h3 class="text-xl font-bold mb-2">Specialized tools</h3>
           <p class="text-sm text-blue-100 mb-6 leading-relaxed">PowerMTA for high-volume sending, Momentum MTA for custom control, recipient validation, inbox tracking, and competitive intelligence.</p>
           <a href="#" class="text-white font-medium text-sm flex items-center gap-1 hover:gap-2 transition-all">
             Learn more <Icon name="arrow-right" className="w-3 h-3" />
           </a>
        </div>
        
        <!-- Decoration Card -->
        <div class="bg-blue-500/10 rounded-2xl p-8 flex items-center justify-center border border-white/5">
           <div class="grid grid-cols-12 gap-2 w-full h-full opacity-20">
              {#each Array(48) as _}
                 <div class="w-1 h-1 bg-white rounded-full"></div>
              {/each}
           </div>
        </div>
      </div>
    </div>
  </div>
</section>

<script>
  import Icon from './Icon.svelte';
  
  const features = [
    {
      icon: 'database',
      title: 'Customer Data Platform',
      desc: 'Every signal, unified and current',
      color: 'bg-blue-100 text-blue-600'
    },
    {
      icon: 'layout',
      title: 'Custom Data Modeling',
      desc: 'Objects and segments for your business',
      color: 'bg-purple-100 text-purple-600'
    },
    {
      icon: 'share-2',
      title: 'Multichannel Orchestration',
      desc: 'Reach customers anywhere',
      color: 'bg-green-100 text-green-600'
    },
    {
      icon: 'sparkles',
      title: 'Smart Personalization',
      desc: 'Marketing that runs itself',
      color: 'bg-orange-100 text-orange-600'
    },
    {
      icon: 'shield',
      title: 'Enterprise Infrastructure',
      desc: 'APIs and security that scale',
      color: 'bg-gray-100 text-gray-600'
    },
    {
      icon: 'bar-chart',
      title: 'Predictive Analytics',
      desc: 'See revenue before it happens',
      color: 'bg-pink-100 text-pink-600'
    }
  ];
</script>

<section class="py-20 px-6 max-w-7xl mx-auto">
  <div class="mb-16">
    <h2 class="text-4xl font-bold text-gray-900 mb-4">Get to know Bird.</h2>
    <p class="text-xl text-gray-600">AI-powered customer lifecycle management that delivers results.</p>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
    {#each features as feature}
      <div class="bg-gray-50 rounded-2xl p-8 hover:bg-gray-100 transition-colors">
        <div class="w-10 h-10 rounded-lg {feature.color} flex items-center justify-center mb-6">
          <!-- Placeholder Icons -->
          <div class="w-5 h-5 bg-current opacity-20 rounded-sm"></div>
        </div>
        <h3 class="text-lg font-semibold text-gray-900 mb-2">{feature.title}</h3>
        <p class="text-gray-600">{feature.desc}</p>
      </div>
    {/each}
  </div>
</section>

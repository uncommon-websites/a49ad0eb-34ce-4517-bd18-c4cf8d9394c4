<script lang="ts">
  let selectedColor = 'white';
</script>

<section class="bg-[#f9f9f7] py-24 px-6">
  <div class="max-w-[1200px] mx-auto text-center">
    <h2 class="text-[40px] font-light text-gray-900 mb-16">
      Three sizes. <span class="text-gray-400">Perfect for every RV.</span>
    </h2>

    <div class="mb-8">
      <h3 class="text-2xl font-normal mb-2">Pro+ Formula</h3>
      <p class="text-gray-500 text-sm">Maximum coverage for large RVs.</p>
    </div>

    <!-- Product Display -->
    <div class="relative w-full h-[400px] bg-white rounded-xl mb-8 flex items-center justify-center overflow-hidden shadow-sm">
      <div class="absolute inset-0 flex items-center justify-between px-4">
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m15 18-6-6 6-6"/></svg>
        </button>
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
        </button>
      </div>
      <img src="https://images.unsplash.com/photo-1585421514738-01798e348b17?q=80&w=2070&auto=format&fit=crop" class="h-[60%] object-contain" alt="Product Bottle" />
    </div>

    <!-- Size Options -->
    <div class="flex justify-center gap-4 mb-8">
      <button class="w-16 h-16 rounded-lg bg-primary-100 border-2 border-primary-500 ring-2 ring-offset-2 ring-primary-200 flex items-center justify-center text-xs font-medium">32oz</button>
      <button class="w-16 h-16 rounded-lg bg-gray-100 border-2 border-gray-200 flex items-center justify-center text-xs font-medium hover:bg-gray-200">64oz</button>
      <button class="w-16 h-16 rounded-lg bg-gray-100 border-2 border-gray-200 flex items-center justify-center text-xs font-medium hover:bg-gray-200">128oz</button>
    </div>

    <div class="flex justify-center gap-8 text-sm text-gray-600 mb-4 border-b border-gray-200 pb-4 inline-flex mx-auto w-auto px-12">
      <span>32 fl oz</span>
      <span>Covers 40 ft RV</span>
      <span>Lasts 4-6 weeks</span>
    </div>

    <p class="text-xs text-gray-500 mb-8">
      Starting at <span class="font-bold text-gray-900">$34.99</span> with free shipping over $50.<br>
      Subscribe and save 15%. ⓘ
    </p>

    <div class="flex justify-center gap-4">
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors text-left">
        <span class="block text-[10px] text-gray-500">Want to compare?</span>
        <span class="text-primary-600">View all sizes</span>
      </button>
      <button class="px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="8" cy="21" r="1"/><circle cx="19" cy="21" r="1"/><path d="M2.05 2.05h2l2.66 12.42a2 2 0 0 0 2 1.58h9.78a2 2 0 0 0 1.95-1.57l1.65-7.43H5.12"/></svg>
        Add to cart
      </button>
    </div>
  </div>
</section>

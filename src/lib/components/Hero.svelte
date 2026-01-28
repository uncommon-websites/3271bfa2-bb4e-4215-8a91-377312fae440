<script lang="ts">
  // Hero component
</script>

<section class="pt-32 pb-20 md:pt-40 md:pb-32 overflow-hidden bg-gradient-to-b from-emerald-50/30 to-white">
  <div class="container-custom">
    <div class="grid lg:grid-cols-2 gap-16 items-center">
      <!-- Left Column: Content -->
      <div>
        <!-- Badge -->
        <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-emerald-100 border border-emerald-200 text-emerald-800 text-sm font-medium mb-8">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"/>
            <polyline points="22 4 12 14.01 9 11.01"/>
          </svg>
          Certified CPA, MBA & Software Expert
        </div>

        <!-- Headline -->
        <h1 class="text-5xl md:text-6xl lg:text-7xl font-bold tracking-tight text-gray-900 mb-6 leading-[1.05]">
          Transform your landscape business into a <span class="text-emerald-600">profit powerhouse</span>
        </h1>

        <!-- Subheadline -->
        <p class="text-xl text-gray-600 mb-10 leading-relaxed">
          Expert consulting for landscape companies earning $1M-$100M. Increase your net profitability from 1-3% to industry-leading margins through data-driven strategy and operational excellence.
        </p>

        <!-- Stats -->
        <div class="grid grid-cols-3 gap-6 mb-10 pb-10 border-b border-gray-200">
          <div>
            <div class="text-3xl font-bold text-emerald-600 mb-1">5-10%</div>
            <div class="text-sm text-gray-600">Target profit margin</div>
          </div>
          <div>
            <div class="text-3xl font-bold text-emerald-600 mb-1">$1M+</div>
            <div class="text-sm text-gray-600">Client revenue range</div>
          </div>
          <div>
            <div class="text-3xl font-bold text-emerald-600 mb-1">100%</div>
            <div class="text-sm text-gray-600">Certified expertise</div>
          </div>
        </div>

        <!-- CTA Buttons -->
        <div class="flex flex-col sm:flex-row items-start gap-4">
          <a href="#contact" class="px-8 py-4 text-base font-semibold bg-emerald-600 text-white rounded-lg hover:bg-emerald-700 transition-colors">
            Schedule free consultation
          </a>
          <a href="#expertise" class="px-8 py-4 text-base font-semibold border-2 border-gray-300 text-gray-700 rounded-lg hover:border-emerald-600 hover:text-emerald-600 transition-colors bg-white">
            Learn about our approach
          </a>
        </div>
      </div>

      <!-- Right Column: Image -->
      <div class="relative">
        <div class="relative rounded-2xl overflow-hidden border border-gray-200 bg-white p-8">
          <!-- Credentials Display -->
          <div class="space-y-6">
            <div class="flex items-start gap-4 p-6 bg-emerald-50 rounded-xl border border-emerald-100">
              <div class="w-12 h-12 rounded-full bg-emerald-600 flex items-center justify-center flex-shrink-0">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                  <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"/>
                  <polyline points="22 4 12 14.01 9 11.01"/>
                </svg>
              </div>
              <div>
                <h3 class="font-bold text-gray-900 mb-1">Certified Public Accountant</h3>
                <p class="text-sm text-gray-600">Deep financial analysis expertise</p>
              </div>
            </div>

            <div class="flex items-start gap-4 p-6 bg-blue-50 rounded-xl border border-blue-100">
              <div class="w-12 h-12 rounded-full bg-blue-600 flex items-center justify-center flex-shrink-0">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                  <path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/>
                  <path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"/>
                </svg>
              </div>
              <div>
                <h3 class="font-bold text-gray-900 mb-1">Master of Business Administration</h3>
                <p class="text-sm text-gray-600">Strategic business leadership</p>
              </div>
            </div>

            <div class="flex items-start gap-4 p-6 bg-purple-50 rounded-xl border border-purple-100">
              <div class="w-12 h-12 rounded-full bg-purple-600 flex items-center justify-center flex-shrink-0">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                  <rect x="2" y="3" width="20" height="14" rx="2" ry="2"/>
                  <line x1="8" y1="21" x2="16" y2="21"/>
                  <line x1="12" y1="17" x2="12" y2="21"/>
                </svg>
              </div>
              <div>
                <h3 class="font-bold text-gray-900 mb-1">Certified Software Specialist</h3>
                <p class="text-sm text-gray-600">Expert in landscape management systems</p>
              </div>
            </div>
          </div>

          <!-- Decorative Element -->
          <div class="absolute -top-4 -right-4 w-24 h-24 bg-emerald-100 rounded-full opacity-50 blur-2xl"></div>
          <div class="absolute -bottom-4 -left-4 w-32 h-32 bg-blue-100 rounded-full opacity-50 blur-2xl"></div>
        </div>
      </div>
    </div>
  </div>
</section>

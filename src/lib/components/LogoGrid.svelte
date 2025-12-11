<script>
    const logos = [
        { name: 'Beiersdorf', hasCaseStudy: false },
        { name: 'Nestlé', hasCaseStudy: false },
        { name: 'Coca-Cola', hasCaseStudy: false },
        { name: 'Dr. Oetker', hasCaseStudy: false },
        { name: 'Kühne', hasCaseStudy: false },
        { name: 'Bahlsen', hasCaseStudy: false },
        { name: 'Unilever', hasCaseStudy: false },
        { name: 'Mondelēz', hasCaseStudy: false },
        { name: 'Henkel', hasCaseStudy: false },
        { name: 'Ferrero', hasCaseStudy: false },
        { name: 'Danone', hasCaseStudy: false },
        { name: 'Mars', hasCaseStudy: false },
        { name: 'P&G', hasCaseStudy: false },
        { name: 'Ritter Sport', hasCaseStudy: false },
        { name: 'Haribo', hasCaseStudy: false }
    ];
</script>

<section class="py-12 bg-white border-b border-gray-200 font-sans">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <p class="text-center text-[10px] uppercase tracking-widest text-brand-green font-bold mb-8">
            Trusted by Innovation Teams at Leading FMCG Brands
        </p>

        <div class="grid grid-cols-2 md:grid-cols-5 gap-0 border-t border-l border-gray-200">
            {#each logos as logo}
                <div class="flex items-center justify-center p-6 border-r border-b border-gray-200 h-24 relative group">
                    <!-- Logo Placeholder -->
                    <span class="text-lg md:text-xl font-bold text-gray-400 group-hover:text-gray-900 transition-colors">
                        {logo.name}
                    </span>

                    {#if logo.hasCaseStudy}
                        <a href="#" class="absolute top-2 right-2 text-[8px] font-bold text-pink-600 bg-pink-50 px-1.5 py-0.5 rounded border border-pink-100 hover:bg-pink-100 flex items-center transition-colors">
                            {logo.caseStudyText} 
                            <svg class="w-2 h-2 ml-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                        </a>
                    {/if}
                </div>
            {/each}
        </div>
    </div>
</section>

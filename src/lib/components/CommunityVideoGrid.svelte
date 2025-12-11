<section class="py-24 bg-white border-t border-gray-200 font-sans">
    <div class="max-w-7xl mx-auto px-4 text-center mb-16">
        <span class="text-[10px] font-bold text-gray-500 uppercase tracking-widest border border-gray-200 px-3 py-1.5 rounded-full bg-gray-50">Trusted Data Sources</span>
        <h2 class="mt-8 text-5xl md:text-6xl font-serif-display text-gray-900">Grounded in <br/> real behavioral data</h2>
        <p class="mt-6 text-gray-600 max-w-2xl mx-auto">Our AI panels are trained on behavioral data from the world's most trusted research organizations. Real data, real insights.</p>
    </div>

    <!-- Data Source Logos Grid -->
    <div class="max-w-7xl mx-auto px-4">
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
            {#each ['Nielsen', 'GfK', 'Eurostat', 'Kantar', 'Statista', 'Ipsos', 'YouGov', 'Destatis'] as source}
            <div class="aspect-video bg-white border border-gray-200 rounded-lg overflow-hidden flex items-center justify-center group hover:border-brand-green transition-colors">
                <span class="text-2xl font-bold text-gray-400 group-hover:text-gray-900 transition-colors">{source}</span>
            </div>
            {/each}
        </div>
        
        <!-- Trust Statement -->
        <div class="mt-16 text-center max-w-3xl mx-auto">
            <p class="text-lg text-gray-600 leading-relaxed">
                Our AI panels are trained on aggregated, anonymized behavioral data from these trusted sources. 
                <span class="text-gray-900 font-medium">Every data point is traceable, every methodology is transparent.</span>
            </p>
            <div class="mt-8 flex items-center justify-center gap-6 text-sm text-gray-500">
                <div class="flex items-center gap-2">
                    <svg class="w-5 h-5 text-brand-green" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                    <span>GDPR Compliant</span>
                </div>
                <div class="flex items-center gap-2">
                    <svg class="w-5 h-5 text-brand-green" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                    <span>EU Hosted</span>
                </div>
                <div class="flex items-center gap-2">
                    <svg class="w-5 h-5 text-brand-green" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                    <span>Anonymized Data</span>
                </div>
            </div>
        </div>
    </div>
</section>

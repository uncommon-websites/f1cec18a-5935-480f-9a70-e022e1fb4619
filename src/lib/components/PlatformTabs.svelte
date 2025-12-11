<script>
    // No script logic needed for this static recreation yet
</script>

<section class="py-20 bg-white font-sans">
    <div class="max-w-7xl mx-auto px-4 text-center">
        <span class="text-[10px] font-bold text-gray-500 uppercase tracking-widest border border-gray-200 px-3 py-1.5 rounded-full bg-gray-50">AI-Powered Consumer Insights</span>
        <h2 class="mt-8 text-5xl md:text-7xl font-serif-display text-gray-900 leading-tight">Test concepts <br/> with confidence, <br/> launch with speed</h2>
    </div>
    
    <!-- Tabbed interface image area -->
    <div class="max-w-7xl mx-auto mt-16 px-4">
        <div class="border border-gray-200 rounded-xl overflow-hidden shadow-sm bg-white grid md:grid-cols-12 min-h-[600px]">
             <div class="md:col-span-4 p-8 md:p-12 border-r border-gray-200 flex flex-col justify-center">
                 <h3 class="text-3xl font-serif-display mb-4">AI panels trained on real consumer behavior</h3>
                 <p class="text-gray-600 text-base leading-relaxed mb-8">Our AI personas are grounded in behavioral data from Nielsen, GfK, Eurostat, Kantar, and more. Each response includes a Confidence Score showing how closely it matches traditional panel results—up to 89% accuracy. Test packaging, pricing, concepts, and messaging with the speed of AI and the reliability of real research.</p>
                 <div>
                    <button class="text-sm font-bold border-b border-gray-300 pb-0.5 hover:border-gray-900 transition-colors">Learn More -></button>
                 </div>
             </div>
             <div class="md:col-span-8 bg-gray-50 p-8 md:p-12 flex items-center justify-center relative overflow-hidden">
                 <!-- Simplified UI Mockup -->
                 <div class="bg-white shadow-xl rounded-lg w-full h-full border border-gray-200 p-6 relative flex flex-col">
                    <div class="flex gap-2 mb-6 border-b border-gray-100 pb-4">
                        <div class="w-3 h-3 rounded-full bg-red-400"></div>
                        <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
                        <div class="w-3 h-3 rounded-full bg-green-400"></div>
                        <div class="ml-auto flex gap-2">
                            <div class="h-4 w-32 bg-gray-100 rounded-full"></div>
                        </div>
                    </div>
                    
                    <div class="space-y-6">
                        <!-- Header Stats -->
                        <div class="grid grid-cols-4 gap-4">
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Responses</div>
                                 <div class="text-xl font-bold text-gray-900">500</div>
                                 <div class="text-[10px] text-green-600 font-bold">3 min</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Confidence</div>
                                 <div class="text-xl font-bold text-gray-900">89%</div>
                                 <div class="text-[10px] text-green-600 font-bold">High</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Cost</div>
                                 <div class="text-xl font-bold text-gray-900">€49</div>
                                 <div class="text-[10px] text-green-600 font-bold">vs €4.9k</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Speed</div>
                                 <div class="text-xl font-bold text-gray-900">10x</div>
                                 <div class="text-[10px] text-gray-400 font-bold">Faster</div>
                             </div>
                        </div>

                        <!-- Data Table -->
                        <div class="border border-gray-100 rounded-lg overflow-hidden">
                            <div class="bg-gray-50 px-4 py-2 border-b border-gray-100 flex text-[10px] font-bold text-gray-500 uppercase tracking-wider">
                                <div class="w-2/5">Concept</div>
                                <div class="w-1/5 text-right">Purchase Intent</div>
                                <div class="w-1/5 text-right">Price Sensitivity</div>
                                <div class="w-1/5 text-right">Confidence</div>
                            </div>
                            <div class="divide-y divide-gray-50 text-xs">
                                 {#each [
                                     {concept: 'Organic Protein Bar', intent: '72%', price: 'Medium', conf: '89%'},
                                     {concept: 'Sugar-Free Energy Drink', intent: '68%', price: 'Low', conf: '91%'},
                                     {concept: 'Plant-Based Yogurt', intent: '65%', price: 'High', conf: '87%'},
                                     {concept: 'Keto Snack Mix', intent: '61%', price: 'Medium', conf: '85%'},
                                     {concept: 'Probiotic Smoothie', intent: '58%', price: 'High', conf: '88%'}
                                 ] as item}
                                 <div class="px-4 py-3 flex items-center hover:bg-gray-50 transition-colors">
                                     <div class="w-2/5 font-medium text-gray-900">{item.concept}</div>
                                     <div class="w-1/5 text-right text-gray-600">{item.intent}</div>
                                     <div class="w-1/5 text-right">
                                         <span class="px-1.5 py-0.5 rounded text-[10px] font-bold {item.price === 'High' ? 'bg-red-100 text-red-700' : item.price === 'Medium' ? 'bg-yellow-100 text-yellow-700' : 'bg-green-100 text-green-700'}">{item.price}</span>
                                     </div>
                                     <div class="w-1/5 text-right">
                                         <span class="text-[10px] font-bold text-brand-green">{item.conf}</span>
                                     </div>
                                 </div>
                                 {/each}
                            </div>
                        </div>
                    </div>
                 </div>
             </div>
        </div>
        
        <!-- Bottom Grid of 3 items -->
        <div class="grid md:grid-cols-3 gap-0 mt-0 border-x border-b border-gray-200 divide-x divide-gray-200 bg-white">
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">1</div>
                <p class="text-xs text-gray-600 leading-relaxed">Upload concepts in any format—text, PDF, PowerPoint. Our AI understands your product positioning and category context.</p>
            </div>
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">2</div>
                <p class="text-xs text-gray-600 leading-relaxed">Get instant feedback from AI panels trained on real FMCG consumer behavior—purchase intent, price sensitivity, and more.</p>
            </div>
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">3</div>
                <p class="text-xs text-gray-600 leading-relaxed">Every insight includes a Confidence Score showing correlation with traditional research—transparent and validated.</p>
            </div>
        </div>
    </div>
</section>
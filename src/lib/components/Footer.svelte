<script>
    // Footer component
</script>

<footer class="bg-brand-dark text-white pt-32 pb-12 overflow-hidden relative font-sans">
    <div class="max-w-7xl mx-auto px-4 relative z-10">
        <div class="text-center mb-24">
             <span class="text-[10px] font-bold uppercase tracking-widest border border-white/20 px-3 py-1.5 rounded-full mb-8 inline-block">Join Closed Beta</span>
             <h2 class="text-5xl md:text-7xl font-serif-display mb-6">Ready to innovate<br/> 10x faster?</h2>
             <p class="text-gray-400 mb-10 max-w-lg mx-auto text-sm">Join the waitlist for early access to TheConsumer AI. Limited spots available for FMCG innovation teams.</p>
             
             <div class="flex flex-col sm:flex-row justify-center gap-2 max-w-md mx-auto">
                 <input type="email" placeholder="Enter your work email" class="bg-white/5 border border-white/10 rounded-lg px-4 py-3 w-full text-white placeholder-gray-500 focus:outline-none focus:border-brand-green transition-colors" />
                 <button class="bg-brand-green hover:bg-brand-green-hover text-white px-6 py-3 rounded-lg font-bold whitespace-nowrap transition-colors flex items-center justify-center">
                     Join Waitlist 
                     <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                 </button>
             </div>
        </div>

        <div class="grid md:grid-cols-4 gap-12 border-t border-white/10 pt-16">
            <div>
                <h3 class="font-bold mb-6">Frequently Asked Questions</h3>
            </div>
            <div class="md:col-span-3 space-y-6">
                {#each ['How is AirOps different from other generative AI tools?', 'What types of content can I create on AirOps?', 'How does AirOps help me beyond content creation?', 'What if I already use an SEO agency?', 'How does pricing work?'] as q}
                <div class="border-b border-white/10 pb-6 flex justify-between items-center cursor-pointer group">
                    <span class="text-lg font-light group-hover:text-brand-green transition-colors">{q}</span>
                    <span class="text-2xl font-light">+</span>
                </div>
                {/each}
            </div>
        </div>

        <div class="grid grid-cols-2 md:grid-cols-5 gap-8 mt-24 text-sm text-gray-400">
            <div>
                <h4 class="text-white font-bold mb-4">Product</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white">Platform</a></li>
                    <li><a href="#" class="hover:text-white">Integrations</a></li>
                    <li><a href="#" class="hover:text-white">Action</a></li>
                    <li><a href="#" class="hover:text-white">Grid</a></li>
                    <li><a href="#" class="hover:text-white">Workflows</a></li>
                    <li><a href="#" class="hover:text-white">Knowledge Base</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-bold mb-4">Solutions</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white">Content Strategy</a></li>
                    <li><a href="#" class="hover:text-white">Marketing Agencies</a></li>
                    <li><a href="#" class="hover:text-white">Content Refresh</a></li>
                    <li><a href="#" class="hover:text-white">Content Creation</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-bold mb-4">General</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white">Pricing</a></li>
                    <li><a href="#" class="hover:text-white">Careers</a></li>
                    <li><a href="#" class="hover:text-white">Documentation</a></li>
                    <li><a href="#" class="hover:text-white">Affiliate</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-bold mb-4">Resources</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white">Academy</a></li>
                    <li><a href="#" class="hover:text-white">Blog</a></li>
                    <li><a href="#" class="hover:text-white">AirOps Research</a></li>
                    <li><a href="#" class="hover:text-white">SEO AI Leader Playbook</a></li>
                    <li><a href="#" class="hover:text-white">SEO Analysis</a></li>
                    <li><a href="#" class="hover:text-white">AirOps vs Writer</a></li>
                    <li><a href="#" class="hover:text-white">AirOps vs Jasper</a></li>
                    <li><a href="#" class="hover:text-white">Prompts</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white font-bold mb-4">Support</h4>
                <ul class="space-y-2">
                    <li><a href="#" class="hover:text-white">Talk to Us</a></li>
                    <li><a href="#" class="hover:text-white">Community</a></li>
                    <li><a href="#" class="hover:text-white">AirOps Job Board</a></li>
                    <li><a href="#" class="hover:text-white">Events</a></li>
                </ul>
            </div>
        </div>
        
        <div class="mt-32 text-center relative">
             <h1 class="text-[12rem] md:text-[16rem] font-bold tracking-tighter leading-none text-white select-none">airops</h1>
             <div class="absolute bottom-4 right-0 flex gap-4 text-[10px] text-gray-500 uppercase tracking-widest">
                 <a href="#">Privacy Policy</a>
                 <a href="#">Terms</a>
                 <a href="#">Contact</a>
             </div>
        </div>
    </div>
</footer>

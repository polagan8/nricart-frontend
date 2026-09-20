NRICart GSAP homepage prototype

Open index.html in a modern browser. It uses:
- GSAP 3.13.0 + ScrollTrigger from jsDelivr
- Supabase for live product loading
- Local generated editorial image assets in /assets

Main motion:
1. Hero entrance timeline
2. Hero scroll parallax/composition
3. Scroll reveals
4. Pinned horizontal pickle journey
5. Subtle image/map parallax
6. Restrained magnetic buttons
7. Product-card entrance after Supabase loads

For production, move the inline CSS/JS into your Next.js/React structure and
keep the Supabase anon key in the public client configuration as appropriate;
never expose service-role secrets in the browser.

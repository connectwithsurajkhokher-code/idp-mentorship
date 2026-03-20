<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8"/>
    <meta content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" name="viewport"/>
    <title>Grow with IDP | 7 PM Live Bootcamp | Suraj Khokher</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700;900&family=Inter:wght@400;500;600&family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,1,0&display=swap" rel="stylesheet"/>
    <script src="https://cdn.tailwindcss.com?plugins=forms"></script>
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: "#9e0000",
                        "primary-light": "#cc0000",
                        luxury: "#faf9f6",
                        executive: "#1a1c1a"
                    },
                    fontFamily: {
                        headline: ["Montserrat", "sans-serif"],
                        body: ["Inter", "sans-serif"]
                    }
                }
            }
        }
    </script>
    
    <style>
        .premium-gradient { background: linear-gradient(135deg, #9e0000 0%, #cc0000 100%); }
        .glass-card { background: rgba(255, 255, 255, 0.8); backdrop-filter: blur(12px); border: 1px solid rgba(255, 255, 255, 0.3); }
        .hide-scrollbar::-webkit-scrollbar { display: none; }
    </style>
</head>

<body class="bg-luxury text-executive font-body antialiased selection:bg-primary/20">

    <nav class="fixed top-0 w-full z-50 bg-white/90 backdrop-blur-md border-b border-neutral-100">
        <div class="flex justify-between items-center max-w-7xl mx-auto px-6 h-16">
            <div class="text-2xl font-black tracking-tighter font-headline">IDP<span class="text-primary">.</span></div>
            <div class="hidden md:flex gap-8 text-xs font-bold uppercase tracking-widest text-neutral-500">
                <a href="#" class="hover:text-primary transition-colors">Bootcamp</a>
                <a href="#" class="hover:text-primary transition-colors">Curriculum</a>
                <a href="#" class="hover:text-primary transition-colors">Testimonials</a>
            </div>
            <button onclick="document.getElementById('reg-form').scrollIntoView({behavior: 'smooth'})" class="bg-primary text-white px-6 py-2 rounded-full font-bold text-xs hover:bg-primary-light transition-all active:scale-95 shadow-lg shadow-primary/20">BOOK SEAT</button>
        </div>
    </nav>

    <main class="pt-16">
        <section class="relative pt-12 pb-20 px-6 overflow-hidden">
            <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-12 items-center">
                <div class="space-y-8 relative z-10">
                    <div class="inline-flex items-center gap-2 bg-primary/10 text-primary px-4 py-1.5 rounded-full text-[10px] font-bold tracking-[0.2em] uppercase">
                        <span class="flex h-2 w-2 rounded-full bg-primary animate-pulse"></span>
                        Join the 7:00 PM Live Bootcamp
                    </div>
                    <h1 class="text-5xl md:text-7xl font-black font-headline leading-[1.1] tracking-tight">
                        Launch Your <br/><span class="text-primary">Digital Empire</span>
                    </h1>
                    <p class="text-lg text-neutral-600 font-medium max-w-md leading-relaxed">
                        Discover the roadmap used by 300,000+ students to achieve financial freedom through high-income digital skills.
                    </p>
                    
                    <div class="glass-card p-6 rounded-3xl shadow-xl max-w-sm flex justify-around items-center border border-white">
                        <div class="text-center">
                            <div class="text-3xl font-black text-primary font-headline">02</div>
                            <div class="text-[9px] uppercase font-black text-neutral-400">Hours</div>
                        </div>
                        <div class="text-2xl font-light text-neutral-200">/</div>
                        <div class="text-center">
                            <div class="text-3xl font-black text-primary font-headline">45</div>
                            <div class="text-[9px] uppercase font-black text-neutral-400">Mins</div>
                        </div>
                        <div class="text-2xl font-light text-neutral-200">/</div>
                        <div class="text-center">
                            <div class="text-3xl font-black text-primary font-headline">12</div>
                            <div class="text-[9px] uppercase font-black text-neutral-400">Secs</div>
                        </div>
                    </div>
                </div>

                <div class="relative group">
                    <div class="aspect-[4/5] rounded-[2rem] overflow-hidden shadow-2xl border-[12px] border-white relative z-10">
                        <img src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?auto=format&fit=crop&q=80&w=800" class="w-full h-full object-cover" alt="Suraj Khokher">
                    </div>
                    <div class="absolute -bottom-6 -right-6 bg-white p-6 rounded-3xl shadow-2xl z-20 flex items-center gap-4">
                        <div class="h-12 w-12 rounded-full bg-primary/10 flex items-center justify-center text-primary">
                            <span class="material-symbols-outlined">verified</span>
                        </div>
                        <div>
                            <div class="text-2xl font-black">300k+</div>
                            <div class="text-[10px] font-bold text-neutral-400 uppercase tracking-widest">Global Successes</div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="py-24 bg-white">
            <div class="max-w-7xl mx-auto px-6">
                <div class="text-center mb-16">
                    <h2 class="text-xs font-black text-primary tracking-[0.3em] uppercase mb-4">The Mentorship Team</h2>
                    <p class="text-4xl font-black font-headline">Learn from the Architects</p>
                </div>
                <div class="grid md:grid-cols-2 gap-12">
                    <div class="group">
                        <div class="aspect-square rounded-[2rem] overflow-hidden mb-6 shadow-lg grayscale group-hover:grayscale-0 transition-all duration-500">
                            <img src="https://images.unsplash.com/photo-1560250097-0b93528c311a?auto=format&fit=crop&q=80&w=600" class="w-full h-full object-cover" alt="Ankit Bansal">
                        </div>
                        <h3 class="text-2xl font-black font-headline">Ankit Bansal</h3>
                        <p class="text-primary font-bold text-xs uppercase tracking-widest">VP, Sales & Execution</p>
                    </div>
                    <div class="group">
                        <div class="aspect-square rounded-[2rem] overflow-hidden mb-6 shadow-lg grayscale group-hover:grayscale-0 transition-all duration-500">
                            <img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?auto=format&fit=crop&q=80&w=600" class="w-full h-full object-cover" alt="Suraj Khokher">
                        </div>
                        <h3 class="text-2xl font-black font-headline">Suraj Khokher</h3>
                        <p class="text-primary font-bold text-xs uppercase tracking-widest">Certified Skill Trainer</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="reg-form" class="py-24 px-6 bg-luxury">
            <div class="max-w-xl mx-auto bg-executive p-10 md:p-14 rounded-[3rem] shadow-2xl text-white relative overflow-hidden">
                <div class="relative z-10">
                    <h2 class="text-3xl font-black font-headline mb-4">Secure Your Spot</h2>
                    <p class="text-neutral-400 text-sm mb-10 leading-relaxed">Seats for the 7 PM session are limited. Reserve yours to get the direct link on WhatsApp.</p>
                    
                    <form id="bootcamp-form" class="space-y-4">
                        <input type="text" id="user-name" placeholder="Your Full Name" required class="w-full bg-white/5 border-white/10 rounded-2xl p-5 text-white focus:ring-primary focus:border-primary placeholder:text-neutral-600"/>
                        <input type="email" id="user-email" placeholder="Email Address" required class="w-full bg-white/5 border-white/10 rounded-2xl p-5 text-white focus:ring-primary focus:border-primary placeholder:text-neutral-600"/>
                        <input type="tel" id="user-phone" placeholder="WhatsApp Number" required class="w-full bg-white/5 border-white/10 rounded-2xl p-5 text-white focus:ring-primary focus:border-primary placeholder:text-neutral-600"/>
                        
                        <button type="submit" class="w-full premium-gradient py-6 rounded-2xl font-black uppercase text-sm tracking-widest hover:brightness-110 active:scale-[0.98] transition-all shadow-xl shadow-primary/30 mt-4">
                            Claim My Seat Now
                        </button>
                    </form>
                </div>
                <div class="absolute top-0 right-0 w-32 h-32 bg-primary/20 blur-[60px] rounded-full"></div>
            </div>
        </section>
    </main>

    <a href="https://wa.me/919675434384" class="fixed bottom-8 right-8 bg-[#25D366] text-white p-4 rounded-full shadow-2xl hover:scale-110 transition-transform z-50">
        <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24"><path d="M12.031 6.172c-3.181 0-5.767 2.586-5.768 5.766-.001 1.298.38 2.27 1.019 3.287l-.582 2.128 2.182-.573c.978.58 1.911.928 3.145.929 3.178 0 5.767-2.587 5.768-5.766.001-3.187-2.575-5.771-5.764-5.771zm3.392 8.244c-.144.405-.837.774-1.17.824-.299.045-.677.063-1.092-.069-.252-.08-.575-.187-.988-.365-1.739-.751-2.874-2.502-2.961-2.617-.087-.116-.708-.94-.708-1.793s.448-1.273.607-1.446c.159-.173.346-.217.462-.217s.231.001.332.005c.109.004.258-.041.404.314l.542 1.312c.058.141.096.305.001.494-.095.188-.145.303-.289.469-.144.166-.303.37-.433.497-.145.141-.297.295-.128.584.168.288.747 1.234 1.601 1.993.854.76 1.574 1.012 1.864 1.157s.462.115.635-.087c.173-.202.743-.865.941-1.163s.396-.245.663-.145c.268.1.1.268 1.704.899.27.106.452.171.512.268.06.096.06.556-.084.961z"></path></svg>
    </a>

    <script>
        document.getElementById('bootcamp-form').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('user-name').value;
            const msg = encodeURIComponent(`Hello Suraj! I just registered for the 7 PM Bootcamp.\n\nName: ${name}`);
            window.location.href = `https://wa.me/919675434384?text=${msg}`;
        });
    </script>
</body>
</html>

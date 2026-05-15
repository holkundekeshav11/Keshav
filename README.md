<!DOCTYPE html>

<html class="dark" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Video Editor Portfolio</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda:ital,opsz,wght@0,6..96,400..900;1,6..96,400..900&amp;family=Geist:wght@100..900&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "tertiary-fixed-dim": "#c8c6c5",
                        "secondary-fixed-dim": "#ffb693",
                        "on-secondary-fixed-variant": "#7a3000",
                        "on-error-container": "#ffdad6",
                        "outline-variant": "#444748",
                        "tertiary": "#c8c6c5",
                        "on-surface": "#e2e2e2",
                        "secondary-container": "#fe6b00",
                        "primary-container": "#0a0a0a",
                        "tertiary-fixed": "#e5e2e1",
                        "on-secondary": "#561f00",
                        "on-primary-fixed": "#1c1b1b",
                        "on-primary-fixed-variant": "#474646",
                        "surface": "#121414",
                        "surface-container-high": "#282a2b",
                        "on-primary-container": "#7b7979",
                        "surface-dim": "#121414",
                        "outline": "#8e9192",
                        "background": "#121414",
                        "error": "#ffb4ab",
                        "on-secondary-container": "#572000",
                        "inverse-surface": "#e2e2e2",
                        "on-tertiary-fixed-variant": "#474746",
                        "on-tertiary-fixed": "#1c1b1b",
                        "on-secondary-fixed": "#351000",
                        "surface-container-lowest": "#0c0f0f",
                        "primary-fixed": "#e5e2e1",
                        "surface-variant": "#333535",
                        "on-tertiary-container": "#7a7979",
                        "surface-bright": "#37393a",
                        "inverse-primary": "#5f5e5e",
                        "secondary": "#ffb693",
                        "on-surface-variant": "#c4c7c7",
                        "surface-tint": "#c9c6c5",
                        "surface-container-low": "#1a1c1c",
                        "surface-container-highest": "#333535",
                        "on-background": "#e2e2e2",
                        "primary": "#c9c6c5",
                        "inverse-on-surface": "#2f3131",
                        "error-container": "#93000a",
                        "on-error": "#690005",
                        "secondary-fixed": "#ffdbcc",
                        "on-tertiary": "#313030",
                        "on-primary": "#313030",
                        "surface-container": "#1e2020",
                        "primary-fixed-dim": "#c9c6c5",
                        "tertiary-container": "#0a0a0a"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.125rem",
                        "lg": "0.25rem",
                        "xl": "0.5rem",
                        "full": "0.75rem"
                    },
                    "spacing": {
                        "container-padding-mobile": "20px",
                        "container-padding-desktop": "40px",
                        "unit": "4px",
                        "gutter": "24px",
                        "component-gap": "12px"
                    },
                    "fontFamily": {
                        "title-sm": ["Geist"],
                        "body-md": ["Geist"],
                        "headline-md": ["Bodoni Moda"],
                        "label-caps": ["Geist"],
                        "display-lg-mobile": ["Bodoni Moda"],
                        "display-lg": ["Bodoni Moda"]
                    },
                    "fontSize": {
                        "title-sm": ["18px", {"lineHeight": "24px", "letterSpacing": "0.05em", "fontWeight": "600"}],
                        "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}],
                        "headline-md": ["32px", {"lineHeight": "40px", "fontWeight": "600"}],
                        "label-caps": ["12px", {"lineHeight": "16px", "letterSpacing": "0.1em", "fontWeight": "700"}],
                        "display-lg-mobile": ["40px", {"lineHeight": "48px", "fontWeight": "700"}],
                        "display-lg": ["64px", {"lineHeight": "72px", "letterSpacing": "-0.02em", "fontWeight": "700"}]
                    }
                }
            }
        }
    </script>
<style>
        .glass-panel {
            background-color: rgba(18, 20, 20, 0.7);
            backdrop-filter: blur(24px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        .btn-primary {
            background-color: #FF6B00;
            color: white;
            transition: all 0.3s ease;
        }
        .btn-primary:hover {
            box-shadow: 0 0 15px rgba(255, 107, 0, 0.5);
        }
        .btn-ghost {
            border: 1px solid rgba(255, 255, 255, 0.2);
            color: white;
            transition: all 0.3s ease;
        }
        .btn-ghost:hover {
            background-color: rgba(255, 255, 255, 0.1);
        }
    </style>
</head>
<body class="bg-background text-on-background min-h-screen selection:bg-secondary-container selection:text-white">
<!-- TopNavBar -->
<nav class="fixed top-0 w-full z-50 bg-surface/80 backdrop-blur-xl border-b border-white/10 flex justify-between items-center px-container-desktop py-4 max-w-full">
<div class="font-headline-md text-headline-md text-on-surface tracking-tighter">STUDIO.EDIT</div>
<div class="hidden md:flex gap-gutter items-center">
<a class="text-on-surface-variant font-title-sm text-title-sm uppercase tracking-widest hover:text-secondary transition-colors duration-300" href="#">Portfolio</a>
<a class="text-on-surface-variant font-title-sm text-title-sm uppercase tracking-widest hover:text-secondary transition-colors duration-300" href="#">Services</a>
<a class="text-on-surface-variant font-title-sm text-title-sm uppercase tracking-widest hover:text-secondary transition-colors duration-300" href="#">Workflow</a>
<a class="text-on-surface-variant font-title-sm text-title-sm uppercase tracking-widest hover:text-secondary transition-colors duration-300" href="#">Pricing</a>
</div>
<div class="flex items-center gap-component-gap">
<button class="hidden md:block btn-primary px-6 py-2 rounded-lg font-label-caps text-label-caps scale-95 active:scale-90 transition-transform">Hire Me</button>
<button class="md:hidden text-on-surface"><span class="material-symbols-outlined">menu</span></button>
</div>
</nav>
<!-- Hero Section -->
<header class="relative min-h-[921px] flex items-center justify-center pt-24 px-container-mobile md:px-container-desktop overflow-hidden">
<div class="absolute inset-0 z-0 bg-cover bg-center opacity-30" style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuA_rlNpzxniAI3oge97eLCNTwi6YqtboCuMZp1W9cxs_PORFgnzIw0GJMnUpoGLTAVer7bNkH31tZuOKZ6gdOWNjG8qAdeLcOWWzdvhYWZMwOa9RZ9yQ5UuaiS24_-VulJVDzCLpGHAyRjJN2tW4bY8pGO-Zj6V0RH6rEb1noIVFsKOE-ovYP9LGYVDkOgOJkiXp9uxEyH9v1FD0JvgH4-YiVrKLzxrMYZRJj57tjfVwVavdR2hWZo0Lto1O-nQ30znyZdLSLvj1WG3');"></div>
<div class="absolute inset-0 z-0 bg-gradient-to-t from-background via-background/80 to-transparent"></div>
<div class="relative z-10 text-center max-w-4xl mx-auto flex flex-col items-center">
<h1 class="font-display-lg-mobile md:font-display-lg text-display-lg-mobile md:text-display-lg text-on-surface mb-6">I Turn Raw Footage Into Viral Stories</h1>
<p class="font-body-md text-body-md text-on-surface-variant mb-10 max-w-2xl">High-impact editing for Reels, YouTube, and Commercials. Designed for retention, crafted with cinematic precision.</p>
<div class="flex flex-col sm:flex-row gap-4 w-full sm:w-auto">
<button class="btn-primary px-8 py-3 rounded-lg font-label-caps text-label-caps flex items-center justify-center gap-2">Book a Call <span class="material-symbols-outlined text-sm">arrow_forward</span></button>
<button class="btn-ghost px-8 py-3 rounded-lg font-label-caps text-label-caps flex items-center justify-center gap-2">View My Work <span class="material-symbols-outlined text-sm">play_circle</span></button>
</div>
</div>
</header>
<!-- About Section -->
<section class="py-24 px-container-mobile md:px-container-desktop border-t border-white/5">
<div class="max-w-7xl mx-auto glass-panel p-8 md:p-12 rounded-xl flex flex-col md:flex-row gap-12 items-center">
<div class="flex-1">
<h2 class="font-headline-md text-headline-md text-on-surface mb-6 border-b border-white/10 pb-4 inline-block">The Art of Retention</h2>
<p class="font-body-md text-body-md text-on-surface-variant mb-4">Editing isn't just about cutting clips together. It's about pacing, emotion, and keeping the viewer hooked from the first frame to the last.</p>
<p class="font-body-md text-body-md text-on-surface-variant">With years of experience in high-end post-production, I specialize in crafting narratives that perform exceptionally across all platforms.</p>
</div>
<div class="flex-1 w-full aspect-video rounded-lg overflow-hidden border border-white/10 relative group">
<img alt="Editor at work" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDsgnVf5r4xvSw4qfVFPr-yCXWLKeViTZM9GIry2PdpfH9hMwjlF5cwewxiYcQQQ8pv2bRq6UiOkQikftwxdhKtenQ0__sH3dzxrNM7g29daM17fTE22wCheoNmlM1wHmGHlqscBKDf0ah-roubmvnMYdi1-WtbeEPEqQf-NEdzKulvYRZ5qBKlIIE704sWwasR6RN2VWiejmEXWVFBjOD5irx9mGXEYSPQjA0huBq48uhqRDRZqPDBIChTRHycTgRle7CYcfsLZsmV"/>
</div>
</div>
</section>
<!-- Services Section -->
<section class="py-24 px-container-mobile md:px-container-desktop bg-surface-container-low">
<div class="max-w-7xl mx-auto">
<h2 class="font-headline-md text-headline-md text-on-surface mb-12 text-center">Technical Expertise</h2>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
<div class="glass-panel p-6 rounded-lg hover:-translate-y-1 transition-transform">
<span class="material-symbols-outlined text-secondary-container text-4xl mb-4">movie</span>
<h3 class="font-title-sm text-title-sm text-on-surface uppercase mb-2">Short-Form</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">High-retention Reels, TikToks, and Shorts with dynamic pacing and captions.</p>
</div>
<div class="glass-panel p-6 rounded-lg hover:-translate-y-1 transition-transform">
<span class="material-symbols-outlined text-secondary-container text-4xl mb-4">smart_display</span>
<h3 class="font-title-sm text-title-sm text-on-surface uppercase mb-2">YouTube Editing</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">Long-form narrative editing designed to maximize AVD and engagement.</p>
</div>
<div class="glass-panel p-6 rounded-lg hover:-translate-y-1 transition-transform">
<span class="material-symbols-outlined text-secondary-container text-4xl mb-4">palette</span>
<h3 class="font-title-sm text-title-sm text-on-surface uppercase mb-2">Color Grading</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">Cinematic color correction and grading in DaVinci Resolve.</p>
</div>
<div class="glass-panel p-6 rounded-lg hover:-translate-y-1 transition-transform">
<span class="material-symbols-outlined text-secondary-container text-4xl mb-4">animation</span>
<h3 class="font-title-sm text-title-sm text-on-surface uppercase mb-2">Motion Graphics</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">Custom animations, lower thirds, and complex visual effects.</p>
</div>
<div class="glass-panel p-6 rounded-lg hover:-translate-y-1 transition-transform">
<span class="material-symbols-outlined text-secondary-container text-4xl mb-4">image</span>
<h3 class="font-title-sm text-title-sm text-on-surface uppercase mb-2">Thumbnail Design</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">High-CTR thumbnails crafted to grab attention instantly.</p>
</div>
<div class="glass-panel p-6 rounded-lg hover:-translate-y-1 transition-transform">
<span class="material-symbols-outlined text-secondary-container text-4xl mb-4">timeline</span>
<h3 class="font-title-sm text-title-sm text-on-surface uppercase mb-2">Content Strategy</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">Consultation on hooks, retention strategies, and channel growth.</p>
</div>
</div>
</div>
</section>
<!-- Portfolio Section -->
<section class="py-24 px-container-mobile md:px-container-desktop border-t border-white/5">
<div class="max-w-7xl mx-auto">
<h2 class="font-headline-md text-headline-md text-on-surface mb-8 text-center">Featured Work</h2>
<div class="flex flex-wrap justify-center gap-4 mb-12">
<button class="btn-primary px-6 py-2 rounded-full font-label-caps text-label-caps">All</button>
<button class="btn-ghost px-6 py-2 rounded-full font-label-caps text-label-caps">Reels</button>
<button class="btn-ghost px-6 py-2 rounded-full font-label-caps text-label-caps">YouTube</button>
<button class="btn-ghost px-6 py-2 rounded-full font-label-caps text-label-caps">Ads</button>
<button class="btn-ghost px-6 py-2 rounded-full font-label-caps text-label-caps">Cinematic</button>
</div>
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
<div class="relative group aspect-video rounded-xl overflow-hidden cursor-pointer">
<img alt="Video thumbnail" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCJC2c93R2CLAwbw3yYZBCDrgr2FpUaU73zaG7_Zyf_vUUbca8euLgVH38h2lnsrThc3IFuF0_SHEjafXBOfldf7cgh7vqJzmeQl9FuyILxw9N0Be9-WwEB1w0212Dv5isE3ob9kAD2K5M6Ow6U61g7lhwfyGF3xhbRS5J6i3PZStW-Wi7kXotjF56eQqQswAHw2j7ztLBnodrTfal-qpICoJFhho_6t3H1hDMvw76OxI3ZRpwvFFBEtHHbElUoM8rR3xqiIvedmmoa"/>
<div class="absolute inset-0 bg-background/80 opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-center justify-center">
<div class="text-center">
<h3 class="font-title-sm text-title-sm text-on-surface mb-2">Tech Brand Anthem</h3>
<p class="font-label-caps text-label-caps text-secondary">Cinematic</p>
</div>
</div>
</div>
<div class="relative group aspect-[9/16] sm:aspect-video rounded-xl overflow-hidden cursor-pointer">
<img alt="Video thumbnail" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD-ydJK0OGB9XsHMzU7s3XYlrIFMohQLVM25cOw84GULc-tXEwjteyoEAjZRC3r2u3ywX1zGL90WU8suDHeDax3-HliDD9Kj_kXwJK11gA31Er2gyb32wPI2KGgkwy30UmkfdC_Zv5Si1O4SQcopHpgYKKBvaUzxrCViWRi-x3f7YwoqtdyvakBJjEQbMaeYk8eRMmqpcOZv1w7ewhcecChSVi_kMpXF9KBXbydgws66vMgbn7437JdwpLOLS30oT4G386McreVmdeI"/>
<div class="absolute inset-0 bg-background/80 opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-center justify-center">
<div class="text-center">
<h3 class="font-title-sm text-title-sm text-on-surface mb-2">Fitness Motivation</h3>
<p class="font-label-caps text-label-caps text-secondary">Reels</p>
</div>
</div>
</div>
<div class="relative group aspect-video rounded-xl overflow-hidden cursor-pointer">
<img alt="Video thumbnail" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAzyfbj3cSPWxtj8vuLNbljClTOIBs41_r5uZiTP6-QzOMXK1Lm1BfGqSjXBvB95psc_3Om1yv_fjbQbDB-25a9gq72jMxIIle6Fnovd260ws0wby9MeWAe7BeOlDUnAl9ybcYje3_0gFJYeZ_PQbSlYvHoGWz-_IhjhLPiDCBnwKbaQGI6V9TO8L1Apb5y6VA9ZFFTe-p1a5q8JD_wc5DaTQRTsUa_mNSfX7srI5_C-XI_4BPb8L7sh860pV7cG1nOBaCZuXnu0TqR"/>
<div class="absolute inset-0 bg-background/80 opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-center justify-center">
<div class="text-center">
<h3 class="font-title-sm text-title-sm text-on-surface mb-2">Product Launch</h3>
<p class="font-label-caps text-label-caps text-secondary">Ads</p>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- Before/After Showcase -->
<section class="py-24 px-container-mobile md:px-container-desktop bg-surface-container-lowest border-t border-white/5">
<div class="max-w-7xl mx-auto">
<h2 class="font-headline-md text-headline-md text-on-surface mb-12 text-center">The Transformation</h2>
<div class="flex flex-col lg:flex-row gap-8">
<div class="flex-1 glass-panel p-6 rounded-xl relative">
<span class="absolute top-4 left-4 bg-surface px-3 py-1 rounded font-label-caps text-label-caps text-on-surface-variant">Raw Footage</span>
<img alt="Raw footage" class="w-full aspect-video object-cover rounded-lg grayscale opacity-70" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBK-RFtaLLw_MWZ-cfOWRzUTn1svZcFDKxbJb6GKSwjkkkEOvmJHiJmf9j4kBwltah7ukNMzyKtXD6t_BLDtGL45vQpBMTyuObvriyBCgxP38v5vVDM1theiyemUv7Xw1AC60QvvDxZq7J0kO0M-vMk8OEiUZWy-SOuzT12HZymN72xjB1CRpEfzxoEtHkdDl8o9CRvz6nQT1r5NPyTLfiyxc-9dee94pOGtbnnxL5LsV-xt5Yrpfr4ACDbzLC8Sknq3ZrDIXWw9KN2"/>
</div>
<div class="flex items-center justify-center -my-4 lg:my-0 lg:-mx-4 z-10">
<span class="material-symbols-outlined text-secondary text-4xl rotate-90 lg:rotate-0 bg-background rounded-full p-2">arrow_forward</span>
</div>
<div class="flex-1 glass-panel p-6 rounded-xl relative border-secondary/30">
<span class="absolute top-4 left-4 bg-secondary px-3 py-1 rounded font-label-caps text-label-caps text-white">Final Story</span>
<img alt="Final edited footage" class="w-full aspect-video object-cover rounded-lg saturate-150 contrast-125" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBGk48X3_OsxkhH4FJIFcKYpOYeAHM31bzCUMG05gHNIC4qyXAeJt2RiLafZ8ON0KKDXRLcpFtsmxt25XiLmtGugCyxzlFwdk8pkdySTAGfcB2dm5O3mG2xnYwY11DXvFAJGKgxVd-bkZHBeaGkqLeIQYdtYUKIAovuZGp7hCxiDydDrS6ygbH4_rnN9cPFLavezqjOEKDG6WGMDcAjPUfr71JBEc9gcH_FQ1Y2RBG4lvULCRn7qKL_hqP0PTnjUQlAwQGxRQXz100R"/>
</div>
</div>
</div>
</section>
<!-- Workflow Process -->
<section class="py-24 px-container-mobile md:px-container-desktop border-t border-white/5">
<div class="max-w-4xl mx-auto">
<h2 class="font-headline-md text-headline-md text-on-surface mb-16 text-center">My Process</h2>
<div class="space-y-12 relative before:absolute before:inset-0 before:ml-5 before:-translate-x-px md:before:mx-auto md:before:translate-x-0 before:h-full before:w-0.5 before:bg-gradient-to-b before:from-transparent before:via-white/20 before:to-transparent">
<div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group">
<div class="flex items-center justify-center w-10 h-10 rounded-full border-2 border-secondary bg-background shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2">
<span class="font-label-caps text-label-caps text-secondary">1</span>
</div>
<div class="w-[calc(100%-4rem)] md:w-[calc(50%-2.5rem)] glass-panel p-6 rounded-xl">
<h3 class="font-title-sm text-title-sm text-on-surface mb-2">Discovery Call</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">We discuss your vision, goals, and the creative direction for the project.</p>
</div>
</div>
<div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group">
<div class="flex items-center justify-center w-10 h-10 rounded-full border-2 border-secondary bg-background shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2">
<span class="font-label-caps text-label-caps text-secondary">2</span>
</div>
<div class="w-[calc(100%-4rem)] md:w-[calc(50%-2.5rem)] glass-panel p-6 rounded-xl">
<h3 class="font-title-sm text-title-sm text-on-surface mb-2">Editing</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">I get to work crafting the narrative, pacing, and visual style.</p>
</div>
</div>
<div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group">
<div class="flex items-center justify-center w-10 h-10 rounded-full border-2 border-secondary bg-background shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2">
<span class="font-label-caps text-label-caps text-secondary">3</span>
</div>
<div class="w-[calc(100%-4rem)] md:w-[calc(50%-2.5rem)] glass-panel p-6 rounded-xl">
<h3 class="font-title-sm text-title-sm text-on-surface mb-2">Review</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">You review the draft and provide feedback for precise refinements.</p>
</div>
</div>
<div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group">
<div class="flex items-center justify-center w-10 h-10 rounded-full border-2 border-secondary bg-background shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2">
<span class="font-label-caps text-label-caps text-secondary">4</span>
</div>
<div class="w-[calc(100%-4rem)] md:w-[calc(50%-2.5rem)] glass-panel p-6 rounded-xl">
<h3 class="font-title-sm text-title-sm text-on-surface mb-2">Delivery</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">Final polished assets are delivered in the optimal formats.</p>
</div>
</div>
<div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group">
<div class="flex items-center justify-center w-10 h-10 rounded-full border-2 border-secondary bg-background shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2">
<span class="font-label-caps text-label-caps text-secondary">5</span>
</div>
<div class="w-[calc(100%-4rem)] md:w-[calc(50%-2.5rem)] glass-panel p-6 rounded-xl">
<h3 class="font-title-sm text-title-sm text-on-surface mb-2">Optimization</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">Analyzing performance and adjusting strategies for future content.</p>
</div>
</div>
</div>
</div>
</section>
<!-- Client Testimonials -->

</div>
</div>
</div>
</div>
</div>
</section>
<!-- Pricing Section -->
<section class="py-12 px-container-mobile md:px-container-desktop border-t border-white/5">
<div class="max-w-7xl mx-auto">
<h2 class="font-headline-md text-headline-md text-on-surface mb-8 text-center">Pricing Plans</h2>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
<!-- Plan 1 -->
<div class="glass-panel p-6 rounded-xl flex flex-col border border-white/10 hover:border-secondary/50 transition-colors">
<h3 class="font-title-sm text-title-sm text-on-surface mb-1 uppercase">Basic</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm mb-4">Perfect for simple cuts and standard edits.</p>
<div class="mb-6">
<span class="font-headline-md text-3xl text-on-surface">$500</span>
<span class="font-body-md text-sm text-on-surface-variant">/project</span>
</div>
<ul class="space-y-2 mb-6 flex-1">
<li class="flex items-start gap-3"><span class="material-symbols-outlined text-secondary text-sm mt-0.5">check</span><span class="font-body-md text-[13px] leading-tight text-on-surface-variant">Up to 5 min final video</span></li>
<li class="flex items-start gap-3"><span class="material-symbols-outlined text-secondary text-sm mt-0.5">check</span><span class="font-body-md text-[13px] leading-tight text-on-surface-variant">Basic color correction</span></li>
<li class="flex items-start gap-3"><span class="material-symbols-outlined text-secondary text-sm mt-0.5">check</span><span class="font-body-md text-[13px] leading-tight text-on-surface-variant">1 Revision round</span></li>
</ul>
<button class="btn-primary w-full py-2.5 rounded-lg font-label-caps text-label-caps">Get Started</button>
</div>
<!-- Plan 2 -->
<div class="glass-panel p-6 rounded-xl flex flex-col border border-secondary relative transform md:-translate-y-2 shadow-[0_0_30px_rgba(255,107,0,0.1)]">
<div class="absolute top-0 left-1/2 -translate-x-1/2 -translate-y-1/2 bg-secondary text-white px-3 py-1 rounded-full font-label-caps text-[10px] tracking-wider">POPULAR</div>
<h3 class="font-title-sm text-title-sm text-on-surface mb-1 uppercase">Growth</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm mb-4">High-retention edits for social media growth.</p>
<div class="mb-6">
<span class="font-headline-md text-3xl text-on-surface">$1,200</span>
<span class="font-body-md text-sm text-on-surface-variant">/project</span>
</div>
<ul class="space-y-2 mb-6 flex-1">
<li class="flex items-start gap-3"><span class="material-symbols-outlined text-secondary text-sm mt-0.5">check</span><span class="font-body-md text-[13px] leading-tight text-on-surface-variant">Up to 15 min final video</span></li>
<li class="flex items-start gap-3"><span class="material-symbols-outlined text-secondary text-sm mt-0.5">check</span><span class="font-body-md text-[13px] leading-tight text-on-surface-variant">Advanced grading &amp; audio</span></li>
<li class="flex items-start gap-3"><span class="material-symbols-outlined text-secondary text-sm mt-0.5">check</span><span class="font-body-md text-[13px] leading-tight text-on-surface-variant">Motion graphics &amp; captions</span></li>
<li class="flex items-start gap-3"><span class="material-symbols-outlined text-secondary text-sm mt-0.5">check</span><span class="font-body-md text-[13px] leading-tight text-on-surface-variant">3 Revision rounds</span></li>
</ul>
<button class="btn-primary w-full py-2.5 rounded-lg font-label-caps text-label-caps">Get Started</button>
</div>
<!-- Plan 3 -->
<div class="glass-panel p-6 rounded-xl flex flex-col border border-white/10 hover:border-secondary/50 transition-colors">
<h3 class="font-title-sm text-title-sm text-on-surface mb-1 uppercase">Premium</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm mb-4">Cinematic quality for commercials and brands.</p>
<div class="mb-6">
<span class="font-headline-md text-3xl text-on-surface">$2,500</span>
<span class="font-body-md text-sm text-on-surface-variant">/project</span>
</div>
<ul class="space-y-2 mb-6 flex-1">
<li class="flex items-start gap-3"><span class="material-symbols-outlined text-secondary text-sm mt-0.5">check</span><span class="font-body-md text-[13px] leading-tight text-on-surface-variant">Unlimited length (within reason)</span></li>
<li class="flex items-start gap-3"><span class="material-symbols-outlined text-secondary text-sm mt-0.5">check</span><span class="font-body-md text-[13px] leading-tight text-on-surface-variant">Cinematic sound design</span></li>
<li class="flex items-start gap-3"><span class="material-symbols-outlined text-secondary text-sm mt-0.5">check</span><span class="font-body-md text-[13px] leading-tight text-on-surface-variant">Custom VFX &amp; Animation</span></li>
<li class="flex items-start gap-3"><span class="material-symbols-outlined text-secondary text-sm mt-0.5">check</span><span class="font-body-md text-[13px] leading-tight text-on-surface-variant">Unlimited revisions</span></li>
</ul>
<button class="btn-primary w-full py-2.5 rounded-lg font-label-caps text-label-caps">Get Started</button>
</div>
<!-- Plan 4 -->
<div class="glass-panel p-6 rounded-xl flex flex-col border border-white/10 hover:border-secondary/50 transition-colors">
<h3 class="font-title-sm text-title-sm text-on-surface mb-1 uppercase">Retainer</h3>
<p class="font-body-md text-body-md text-on-surface-variant text-sm mb-4">Ongoing monthly support for creators.</p>
<div class="mb-6">
<span class="font-headline-md text-3xl text-on-surface">Custom</span>
</div>
<ul class="space-y-2 mb-6 flex-1">
<li class="flex items-start gap-3"><span class="material-symbols-outlined text-secondary text-sm mt-0.5">check</span><span class="font-body-md text-[13px] leading-tight text-on-surface-variant">Guaranteed monthly capacity</span></li>
<li class="flex items-start gap-3"><span class="material-symbols-outlined text-secondary text-sm mt-0.5">check</span><span class="font-body-md text-[13px] leading-tight text-on-surface-variant">Priority turnaround times</span></li>
<li class="flex items-start gap-3"><span class="material-symbols-outlined text-secondary text-sm mt-0.5">check</span><span class="font-body-md text-[13px] leading-tight text-on-surface-variant">Strategy consultation</span></li>
<li class="flex items-start gap-3"><span class="material-symbols-outlined text-secondary text-sm mt-0.5">check</span><span class="font-body-md text-[13px] leading-tight text-on-surface-variant">Discounted volume rates</span></li>
</ul>
<button class="btn-primary w-full py-2.5 rounded-lg font-label-caps text-label-caps">Get Started</button>
</div>
</div>
</div>
</section>
<!-- Contact Section -->
<section class="py-24 px-container-mobile md:px-container-desktop bg-surface-container-low border-t border-white/5">
<div class="max-w-5xl mx-auto">
<div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
<div>
<h2 class="font-headline-md text-headline-md text-on-surface mb-6">Ready to Start?</h2>
<p class="font-body-md text-body-md text-on-surface-variant mb-10">Fill out the form below or reach out directly through my social channels to discuss your next project.</p>
<div class="flex flex-col gap-4">
<button class="btn-ghost px-6 py-4 rounded-lg font-label-caps text-label-caps flex items-center justify-center gap-3 w-full sm:w-auto hover:border-secondary transition-colors text-left">
<span class="material-symbols-outlined">chat</span> WhatsApp Message
                    </button>
<button class="btn-ghost px-6 py-4 rounded-lg font-label-caps text-label-caps flex items-center justify-center gap-3 w-full sm:w-auto hover:border-secondary transition-colors text-left">
<span class="material-symbols-outlined">photo_camera</span> Direct on Instagram
                    </button>
<button class="btn-ghost px-6 py-4 rounded-lg font-label-caps text-label-caps flex items-center justify-center gap-3 w-full sm:w-auto hover:border-secondary transition-colors text-left">
<span class="material-symbols-outlined">mail</span> Send an Email
                    </button>
</div>
</div>
<div class="glass-panel p-8 rounded-xl">
<form class="space-y-6">
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-2" for="name">Name</label>
<input class="w-full bg-surface-variant/50 border border-white/10 rounded-lg px-4 py-3 text-on-surface focus:outline-none focus:border-secondary focus:ring-1 focus:ring-secondary transition-colors" id="name" placeholder="John Doe" type="text"/>
</div>
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-2" for="email">Email</label>
<input class="w-full bg-surface-variant/50 border border-white/10 rounded-lg px-4 py-3 text-on-surface focus:outline-none focus:border-secondary focus:ring-1 focus:ring-secondary transition-colors" id="email" placeholder="john@example.com" type="email"/>
</div>
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-2" for="message">Project Details</label>
<textarea class="w-full bg-surface-variant/50 border border-white/10 rounded-lg px-4 py-3 text-on-surface focus:outline-none focus:border-secondary focus:ring-1 focus:ring-secondary transition-colors" id="message" placeholder="Tell me about your footage..." rows="4"></textarea>
</div>
<button class="btn-primary w-full py-4 rounded-lg font-label-caps text-label-caps" type="button">Submit Inquiry</button>
</form>
</div>
</div>
</div>
</section>
<!-- Footer -->
<footer class="bg-surface-container-lowest border-t border-white/5 grid grid-cols-1 md:grid-cols-2 gap-gutter px-container-desktop py-12 w-full">
<div>
<div class="font-headline-md text-headline-md text-on-surface mb-4 tracking-tighter">STUDIO.EDIT</div>
<p class="font-label-caps text-label-caps text-on-surface-variant opacity-80">© 2024 STUDIO.EDIT. ALL RIGHTS RESERVED.</p>
</div>
<div class="flex flex-wrap gap-4 md:justify-end items-center">
<a class="font-label-caps text-label-caps text-on-surface-variant hover:text-secondary transition-colors opacity-80 hover:opacity-100" href="#">Instagram</a>
<a class="font-label-caps text-label-caps text-on-surface-variant hover:text-secondary transition-colors opacity-80 hover:opacity-100" href="#">Vimeo</a>
<a class="font-label-caps text-label-caps text-on-surface-variant hover:text-secondary transition-colors opacity-80 hover:opacity-100" href="#">LinkedIn</a>
<a class="font-label-caps text-label-caps text-on-surface-variant hover:text-secondary transition-colors opacity-80 hover:opacity-100" href="#">Twitter</a>
<a class="font-label-caps text-label-caps text-on-surface-variant hover:text-secondary transition-colors opacity-80 hover:opacity-100" href="#">Privacy Policy</a>
<a class="font-label-caps text-label-caps text-on-surface-variant hover:text-secondary transition-colors opacity-80 hover:opacity-100" href="#">Terms</a>
</div>
</footer>
</body></html>

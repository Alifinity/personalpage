<template>
    <header class="fixed top-0 left-0 right-0 z-20 bg-slate-900/80 backdrop-blur-md border-b border-white/5">
        <div class="mx-auto max-w-4xl px-4">
            <div class="flex h-16 items-center justify-end md:justify-center">
                <nav class="hidden md:flex space-x-8 text-sm font-medium">
                    <a href="#about" class="text-slate-300 hover:text-white transition-colors">About</a>
                    <a href="#skills" class="text-slate-300 hover:text-white transition-colors">Skills</a>
                    <a href="#contact" class="text-slate-300 hover:text-white transition-colors">Contact</a>
                </nav>
                <button class="md:hidden text-slate-300 hover:text-white">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24"
                        stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            d="M4 6h16M4 12h16m-7 6h7" />
                    </svg>
                </button>
            </div>
        </div>
    </header>
</template>

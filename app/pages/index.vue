<template>
    <div
        class="min-h-screen bg-black p-10 flex items-center justify-center bg-back-pattern bg-contain bg-center bg-no-repeat">

        <aside class="w-28 bg-transparent text-white p-6">
            <h2 class="text-xl font-bold mb-8">Menu</h2>
            <nav class="flex flex-col gap-4">
                <NuxtLink title="Home" to="/" class="hover:text-emerald-400">ホーム</NuxtLink>
                <NuxtLink title="About" to="/about" class="hover:text-emerald-400">会社概要</NuxtLink>
                <NuxtLink title="Services" to="/services" class="hover:text-emerald-400">サービス</NuxtLink>
            </nav>
        </aside>

        <main class="flex-1 flexflex-col items-center justify-center bg-transparent p-8 rounded-2xl shadow-xl w-full max-w-md text-center">
            <h1 class="text-3xl font-bold text-emerald-600 mb-4">こんにちは！ らせん</h1>
            <p class="text-slate-600 mb-6">This is the main landing page of the application.</p>
        
        <NuxtLink to="/about"
            class="mt-6 px-4 py-2 bg-emerald-600 text-white rounded-lg hover:bg-emerald-700 transition-colors duration-300">
            Go to About Page
        </NuxtLink>
        </main>


    </div>
</template>
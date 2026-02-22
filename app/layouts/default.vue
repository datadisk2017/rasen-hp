<template>
    <div
        class="min-h-screen bg-black flex items-center justify-center bg-back-pattern bg-contain bg-center bg-no-repeat">

        <aside class="w-26 bg-transparent text-white p-2">
            <h2 class="text-xl font-bold mb-8">Menu</h2>
            <nav class="flex flex-col gap-4">
                <NuxtLink title="Home" to="/" class="hover:text-emerald-400">ホーム</NuxtLink>
                <NuxtLink title="About" to="/about" class="hover:text-emerald-400">会社概要</NuxtLink>
                <NuxtLink title="Services" to="/services" class="hover:text-emerald-400">サービス</NuxtLink>
            </nav>
        </aside>

        <main class="flex-1 flexflex-col items-center justify-center bg-transparent p-4 rounded-2xl shadow-xl w-full max-w-md text-center">
            <slot />
        </main>


    </div>
</template>
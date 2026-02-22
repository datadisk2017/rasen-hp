<template>
    <div class="min-h-screen bg-slate-50 p-10 flex flex-col items-center justify-center">
        <div class="bg-white p-8 rounded-2xl shadow-xl w-full max-w-md text-center">
            <h1 class="text-3xl font-bold text-emerald-600 mb-4">Welcome to the Home Page</h1>
            <p class="text-slate-600 mb-6">This is the main landing page of the application.</p>
        </div>
            <NuxtLink to="/about" class="mt-6 px-4 py-2 bg-emerald-600 text-white rounded-lg hover:bg-emerald-700 transition-colors duration-300">
                Go to About Page
            </NuxtLink>

        
    </div>
</template>
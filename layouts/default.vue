<template>
    <div class="bg-white">
        <header class="p-4">
            <Navigation />
        </header>
        <main>
            <slot />
        </main>
        <footer>
            <MainFooter />
        </footer>
    </div>
</template>
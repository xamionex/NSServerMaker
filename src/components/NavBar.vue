<template>
    <header>
        <div class="text-gray-500 dark:text-gray-400">
            <nav>
                <ul>
                    <router-link class="btn" to="/">Home</router-link>
                    <router-link class="btn" to="/">Mods</router-link>
                    <router-link class="btn" to="about">About</router-link>
                    <button id="theme-toggle" type="button" class="btn">
                        <svg id="theme-toggle-dark-icon" class="hidden w-5 h-5">
                            <use xlink:href="../assets/icons.svg#dark"></use>
                        </svg>
                        <svg id="theme-toggle-light-icon" class="hidden w-5 h-5">
                            <use xlink:href="../assets/icons.svg#light"></use>
                        </svg>
                    </button>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
    export default {
        name: "NavBar",
    };
</script>
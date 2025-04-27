<template>
    <div>
        <header>
            <h2>JS animation</h2>
            <div>
                <router-link to="/"><button id="button-two">CSS анимация</button></router-link>
                <router-link to="/anime"><button id="button-two">AnimeJS</button></router-link>
                <router-link to="/gsap"><button id="button-two">GSAP</button></router-link>

            </div>
        </header>
        <BoxContainer />
    </div>
</template>

<script setup>
import BoxContainer from '@/components/BoxContainer.vue'
</script>
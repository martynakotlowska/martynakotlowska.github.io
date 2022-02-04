<template>
    <v-parallax height="400" src="../assets/background_programming.png">
        <v-container fluid fill-height class="home-hero" style="max-height: 150vh;">
            <v-layout justify-center row wrap  column pa-5>
                <div class="display-4 font-weight-black white--text text-xs-center">Pis<span class="display-4"> - Inżynieria Społeczna</span></div>
                <div class="display-4 font-weight-black white--text text-xs-center mb-3">inż. Martyna Kotłowska</div>
                <div class="display-1 font-weight-bold white--text text-xs-center">Grupa 206C</div>
            </v-layout>
        </v-container>
    </v-parallax>
</template>

<script>
export default {
    name: 'HomeHero'
};
</script>

<style scoped>
.home-hero {
    
    width: 100%;
    height: 100%;
}
</style>
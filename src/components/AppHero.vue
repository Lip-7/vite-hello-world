<template>
    <div class="text-white jumbo p-5 bg-secondary">
        <h2>{{title}}</h2>
        <p>Wellcome to my first site with this technologie</p>
    </div>
</template>

<script>
export default {
    name: 'AppHero',
    data() {
        return {
            title: 'Wellcome to Vite / Node.js',

        }
    }
}
</script>

<style lang="scss" scoped>
    .jumbo{
        width: 100%;
        height: 400px;
        border: 1px solid white;
        border-radius: 50px;
    }
</style>
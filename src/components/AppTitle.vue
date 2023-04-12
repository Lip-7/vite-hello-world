<template>
    <div class="title-wrapper">
        <h1 class="text-white">{{title}}</h1>
    </div>
</template>

<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            title: 'Hello World',
        }
    }
}
</script>

<style lang="scss" scoped>
    .title-wrapper{
        display: flex;
        justify-content: center;
        padding: 20px 0;
    }
</style>
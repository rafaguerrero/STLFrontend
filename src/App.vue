<template>
    <div class="stl-greeting">
        <p class="stl-greeting--title">Test : {{ greeting }} World!</p>
    </div>
</template>

<script>
    export default {
        name: 'App',
        data: function () {
            return { greeting: 'Hello' }
        }
    };
</script>

<style lang="scss" scoped>
    .stl-greeting {
        font-size: 2em;
        text-align: center;

        &--title {
            color : blue;
        }
    }
</style>
<script>
    export default {
        data () {
            return {
                flage: false,
            };
        },

        methods: {
            changeColor() {
                this.flage = !this.flage;
            }
        },
    };
</script>

<template>
    <button @click.stop="changeColor">{{ flage }}</button>
</template>

<style>
</style>
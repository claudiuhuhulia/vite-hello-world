<script>
export default {
    data() {
        return {

        }
    },
    methods: {
        getImagePath() {
            const url = new URL(`../assets/jumbo.jpg`, import.meta.url);
            return url.href;
        }
    }
}
</script>

<template>
    <img :src="getImagePath()" alt="Hero">
</template>
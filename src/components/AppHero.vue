<script>
export default {
    name: 'AppHero',
    data() {
        return {
            image: 'matrix.jpg',
        }
    },
    methods: {
        buildImgPath(img) {
            return new URL(`../assets/img/${img}`, import.meta.url).href
        }
    }
}
</script>

<template>
    <img :src="buildImgPath(image)" alt="matrix">
</template>
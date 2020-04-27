<template>
    <div class="news">
        <news-button-component/>
    </div>
</template>

<script>
import NewsButtonComponent from "../components/NewsComponent.vue"
export default {
    name: "News",
    components: {
        NewsButtonComponent
    }
}
</script>


<style scoped>
.news {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100%;
    margin: auto;
}
</style>
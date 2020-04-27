<template>
    <div class="news-info">
        <div>
            <h1>Presenting Today's News</h1>
        </div>
        <div class="news-button">
            <button v-on:click="logMessage">News Button</button>
        </div>
    </div>
</template>

<script>
export default {
    name: "NewsButtonComponent",
    methods: {
        logMessage() {
            console.log(this.$route.fullPath);
        }
    }
}
</script>


<style scoped>

button {
    background-color:rgb(188, 50, 216);
    border-radius: 5px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    border: none;
    color: white;
    padding: 15px 32px;
    cursor: pointer;
    transition: background-color 0.5s, font-size 0.5s, border-radius 0.5s;
}

button:hover {
    border-radius: 10px;
    background-color:rgb(175, 48, 201);
    font-size: 14px;
    font-weight: bold;
}

.news-info {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin-top: 150px;
}

.news-button {
    
    padding-top: 15px;
}

</style>
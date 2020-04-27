<template>
<div class="home-info">
    <div>
        <h1> This is The Homepage</h1>
    </div>
    <div class="home-button">
        <button>Home Button</button>
    </div>
</div>
</template>


<script>
export default {
    name: "HomeButtonComponent"
}
</script>

<style scoped>
button {
    background-color:rgb(42, 130, 231);
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
    background-color:rgb(65, 88, 189);
    font-size: 14px;
    font-weight: bold;
}

.home-info {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin-top: 150px;
}

.home-button {
    
    padding-top: 15px;
}
</style>
<template>
<div>
    <div>
        <h1> This is the Homepage</h1>
    </div>
    <div>
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
    background-color: rgb(65, 88, 189);
    border-radius: 5px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    border: none;
    color: white;
    padding: 15px 32px;
    cursor: pointer;
}
</style>
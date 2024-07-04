<script>
    export default {
        name: "AppHero",
    }
</script>

<template>
    <div>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla vehicula libero eu nulla viverra, nec volutpat urna suscipit.</p>
        <button>Scopri di più</button>
    </div>
</template>

<style scoped>
    div {
        text-align:center;
        background-color: #54bdc9;
        padding: 25px;
    }

    p {
        font-size: 20px;
        color: #c7eef5;
        line-height: 1.5;
        width: 50%;
        margin: 0 auto;
    }

    button {
        background-color: #022249;
        color: white;
        padding: 10px 20px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        font-size: 16px;
        margin-top: 25px;
    }

    button:hover {
        background-color: #ef7b40;
    }
</style>
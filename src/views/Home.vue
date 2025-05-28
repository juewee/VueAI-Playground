<template>
    <div class="container">
        <h2 style="display: flex;align-items: center;"><img src="/logo.png" alt="" style="height: 80px;width: 80px;"> Describe what you want</h2>
        <div class="chat-box">
            <input type="text">
        </div>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
.container{
    display: flex;
    flex-direction: column;
    height: 100vh;
    width: 100vw;
    justify-content: center;
    align-items: center;
    gap: 8px;
}
.chat-box{
    padding: 20px 0;
    background-color: #3B3B3B;
    box-shadow: var(--el-box-shadow);
    border-radius: 50px;
    width: 60%;
    /* height: 10%; */
    display: flex;
    justify-content: center;
    align-items: center;
}

.chat-box input {
    width: 80%;
    background: transparent;
    border: none;
    outline: none;
    padding: 8px;
    font-size: 16px;
}

</style>
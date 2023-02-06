<script setup>

const {quizData} = defineProps(['quizData'])
console.log(quizData)

</script>

<template>
    <div class="card">
        <img :src="quizData.img" alt="">
        <div class="card-text">
            <h2>{{ quizData.name }}</h2>
            <p>3 questions</p>
        </div>
    </div>
</template>

<style scoped>
.card {
    width: 310px;
    overflow: hidden;
    border: 2%;
    box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.1);
    margin-bottom: 35px;
    margin-right: 20px;
    cursor: pointer;
}

.card img {
    width: 100%;
    display: flex;
    align-items: center;
    margin: 0;
}

.card .card-text {
    padding: 0 5px;
}

.card .card-text h2 {
    font-weight: bold;
}
</style>
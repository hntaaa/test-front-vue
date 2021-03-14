<template>
    <div class="text_card">
        <h1>{{title_text}}</h1>
        <a href=""> Выбрать предложение</a>
    </div>
</template>

<script>
export default {
    name: 'InsuranceCard',
    props: {
        title_text: String
    }
        
}
</script>

<style>
    .text_card{
        margin-top: 1rem;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-around;
        padding: 2rem;
        background-color: #22223a;
        width: 42%;
        height: 200px;
        border-radius: 10px;
    }
    .text_card a{
        border-radius: 10px;
        font-size: 1rem;
        padding: 0.5rem 2rem;
        background-color: #00a847;
        text-decoration: none;
        color: white;
        letter-spacing: 1px;
    }
     .text_card h1{
        font-size: 1.5rem;
        text-decoration: none;
        color: white;
        letter-spacing: 1.5 px;
        font-size: 3rem;
        text-align: center;
    }
</style>
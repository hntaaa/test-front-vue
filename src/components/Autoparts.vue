<template>
    <div class="autoparts">
        <h1>Автозапчасти</h1>
        <div class="cards">
            <AutopartsCard title_text="Фильтры"/>
            <AutopartsCard title_text="Масла"/>
            <AutopartsCard title_text="Колодки"/>
            <AutopartsCard title_text="Аксессуары"/>
            <AutopartsCard title_text="Свечи"/>
            <AutopartsCard title_text="Автолампы"/>
            <AutopartsCard title_text="Щетки"/>
            <AutopartsCard title_text="Автохимия"/> 
        </div>
        <a class="search" href=""> Найти запчасть</a>
       
    </div>
</template>

<script>

import AutopartsCard from '@/components/AutopartsCard.vue'
export default {
    name: 'Autoparts',
    components:{
        AutopartsCard
    }
}
</script>

<style>

    .autoparts{
        margin-top: 3rem;
        width: 100%;
    }
    .autoparts h1{
        text-transform: uppercase;
        font-weight: bold;
        color: white;
        font-size: 1rem;
        letter-spacing: 2px;
        font-weight: bold;
    }
    .cards{
        display: flex;
        flex-wrap: wrap;
        width: 100%;
        justify-content: space-between;
    }
    .search{
        border-radius: 10px;
        font-size: 1rem;
        padding: 0.5rem 2rem;
        background-color: #00a847;
        text-decoration: none;
        color: white;
        letter-spacing: 1px;
        cursor: pointer;
        margin-left: 500px;
    }
</style>
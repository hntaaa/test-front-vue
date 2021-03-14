<template>
    <div class="autolawyer">

        <h1>Автоадвокат</h1>
        <div class="cards">
            <AutolawyerCard title_text="Возмещение ущерба по восстановлению автотранспорта"/>
            <AutolawyerCard title_text="Возмещение упущенной выгоды в результате ДТП"/>
            <AutolawyerCard title_text="Возмещение ущерба при причинении вреда жизни и здоровью"/>
            <AutolawyerCard title_text="Взыскание ущерба, когда виновник не завтрахован"/>
            <AutolawyerCard title_text="Контрорль поиска скрывшегося виновника"/>
            <AutolawyerCard title_text="Возмещение морального вреда"/>            
        </div>
       
    </div>
</template>

<script>

import AutolawyerCard from '@/components/AutolawyerCard.vue'
export default {
    name: 'Autolawyer',
    components:{
        AutolawyerCard
    }
}
</script>

<style>

    .autolawyer{
        margin-top: 3rem;
        width: 100%;
    }
    .autolawyer h1{
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
   
</style>
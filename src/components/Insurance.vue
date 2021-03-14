<template>

    <div class="insurance">
        <h2>Автострахование</h2>
        <div class="cards">
            <InsuranceCard title_text='Обязательное страхование'/>
            <InsuranceCard title_text='Добровольное страхование'/>
        </div>
    </div>

</template>

<script>
import InsuranceCard from '@/components/InsuranceCard.vue'
export default {
    name: 'Insurance',
    components:{
        InsuranceCard
    }
}
</script>

<style>
    .insurance{
        margin-top: 3rem;
    }
    .insurance h2{
        text-transform: uppercase;
        font-weight: bold;
        color: white;
        font-size: 1rem;
        letter-spacing: 2px;
    }
    .insurance .cards{
        display: flex;
    }
</style>
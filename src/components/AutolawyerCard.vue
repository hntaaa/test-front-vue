<template>
    <div class="autolawyer_back">
        <h2>{{title_text}}</h2>
    </div>
</template>

<script>
export default {
    name: 'AutolawyerCard',
    props: {
        title_text: String
    }
}
</script>

<style>

    .autolawyer_back{
        background: #22223a;
        width: 31.5%;
        height: 100px;
        border-radius: 10px;
        margin: 1rem 0;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .autolawyer_back h2{
        font-size: 1rem;
        color: white;
        letter-spacing: 1px;
        padding: 1rem;
    }

</style>
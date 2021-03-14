<template>
    <div class="back">
        <h2>{{title_text}}</h2>
    </div>
</template>

<script>
export default {
    name: 'AutopartsCard',
    props: {
        title_text: String
    }
}
</script>

<style>

    .back{
        position: relative;
        background: #22223a;
        width: 250px;
        height: 100px;
        border-radius: 10px;
        margin: 1rem 0;
    }
    .back h2{
        position: absolute;
        font-size: 1rem;
        color: white;
        text-transform: capitalize;
        letter-spacing: 1px;
        top: 10%;
        left: 15%;
    }

</style>
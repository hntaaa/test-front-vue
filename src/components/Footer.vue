<template>
<div class="footing">

    <div class="footer">
        <div class="links">
            <a href="#">Техпомощь</a>
            <a href="#">Страхование</a>
            <a href="#">Автоадвокат</a>
        </div>
        <div class="mid">
            <h1>Litro</h1>
            <div class="stores">
                <img src="@/assets/apple.png" alt="App Store">
                <img src="@/assets/google.jpg" alt="Google Play Market">
            </div>
        </div>
        <div class="contacts">
            <a href="#">Мы в соц сетях</a>
            <a href="#"><img src="@/assets/insta.jpg" alt="Instagram"></a>
            <a href="#">info@litro.kz</a>
            <a href="#">5070</a>
        </div>
    </div>
</div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style>
    .mid h1{
        display: inline-block;
        font-weight: 400;
        color: white;
        padding: .375rem .75rem;
        font-size: 2rem;
        line-height: 1.5;
        border-radius: .25rem;
        font-weight: bold;
        text-transform: uppercase;
    }

    .footing{
        background-color: #22223a;
        margin-top: 3rem;
        padding: 3rem;
    }
    .footer{
        display: flex;
        justify-content: space-between;
        align-items: center;
        max-width: 1170px;
        margin: 0 auto;
    }

    .stores img{
        width: 100px;
        height: 25px;
        margin-right: 1rem;
        border-radius: 5px;
    }
    .contacts img{
        width: 25px;
        height: 24px;
        border-radius: 50%;
    }
    .footer a{
        font-size: 14px;
        text-decoration: none;
        color: white;
        letter-spacing: 1px;
        padding: 0.3rem 0rem;
    }
    .links{
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
    .mid{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .contacts{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    
</style>
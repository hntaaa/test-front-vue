<template>
    
    <div class="heading">
        <div class="header">
            <div class="logo">
                <h1>LITRO</h1>
            </div>
            <nav>
                <a href="#"> Техпомощь </a>
                <a href="#"> Страхование </a>
                <a href="#"> Автопрокат </a>
            </nav>
            <div class="info">
                <a href="#"> <img src="@/assets/phone.png" alt="Phone"> 8829 </a>
                <a href="#"> <img src="@/assets/map.png" alt="Map"> Almaty </a>
            </div>
            <div class="login">
                <h1>Вход</h1>
            </div>
        </div>
    </div>

</template>

<script>
    export default {
        name: "Header"
    }
</script>


<style>
    .heading{
        background-color: #22223a;
    }
    .header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        max-width: 1170px;
        margin: 0 auto;
    }

    .logo h1{
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
    
    nav a{
        font-size: 0.8rem;
        display: inline-block;
        margin: 0 15px;
        text-decoration: none;
        color: rgb(248, 245, 245);
        position: relative;
        text-transform: uppercase;
        letter-spacing: 1px;
    }   
    nav a:after{
        content: "";
        display: block;
        width: 100%;
        height: 1px;
        background-color: rgb(243, 236, 236);
        position: absolute;
        top: 100%;
        left: 0;
        z-index: 1;
        display: none;
    }
    nav a:hover:after{
        display: block;
    }

    .login h1{
        border-radius: 5px;
        font-size: 0.8rem;
        padding: 0.5rem 1.8rem;
        background-color: #00a847;
        text-decoration: none;
        color: white;
        cursor: pointer;
    }
    .info a{
        font-size: 16px;
        display: inline-block;
        margin: 0 15px;
        text-decoration: none;
        color: rgb(248, 245, 245);
        background-color: #111320;
        padding: 0.3rem;
        text-transform: capitalize;
        letter-spacing: 2px;
        border-radius: 5px;
        border-color: #00a847;
        border: 1px;
    }  

    .info img{
        width: 15px;
        height: 15px;
    }

</style>
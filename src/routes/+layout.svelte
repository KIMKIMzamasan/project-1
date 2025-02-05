<script>
import Title from '$lib/title.svelte';
import '../routes/global.css';
</script>

<header>
    <Title title = 'Mazasankun'/>
    <div class="home">
        <ul>
            <li><a href="/" style="color: aliceblue; font-size: 30px;" >Home</a></li>
        </ul>
    </div>
    <div class="about">
        <ul>
            <li><a href="/about" style="color: aliceblue; font-size: 30px;">About Me</a></li>
        </ul>
    </div>
</header>
<main>
    <slot> </slot>
</main>
<footer>
    <h3 style="color: aliceblue;" >Copy Right 2025 Mazasankun</h3>
    
    <div class="container">
        <div class="sec1">

            <div class="pictures">
                <img src="facebook.svg" alt="">
                <a href="https://www.facebook.com/kimkimsama.cabural.1">czar cabural</a>
            </div>

            <div class="pictures">
                <img src="instagram.svg" alt="">
                <a href="https://www.instagram.com/cabural_czar/">czar_cabural</a>
            </div>

            <div class="pictures">
                <img src="github.svg" alt="">
                <a href="https://github.com/KIMKIMzamasan">KIMKIMzamasan</a>
            </div>

        </div>

        <div class="sec2">
            <div class="pictures">
                <img src="linkedin.svg" alt="">
                <a href="https://www.linkedin.com/in/czar-von-louie-cabural-153a91332/">Czar Von Louie Cbaural</a>
            </div>

            <div class="pictures">
                <img src="gmail.svg" alt="">
                <a href="https://www.gmail.com/">caburalczarvonlouie@gmail.com</a>
            </div>
        </div>
    </div>

    

</footer>

<style>

    header{
        display: flex;
        justify-content: center;
        background-color: #8A2BE2;
    }
    main{
        max-width:1500px ;
        margin: 20px auto;
    }
    footer{
        display: block;
        background-color: #8A2BE2;
        height: 300px;
        padding: 20px;
    }

    footer h3{
        text-align: center;
        font-size: 20px;
    }

    .container{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr;
        justify-content: justify;
    }


    .pictures img{
        width: 30px;
        margin-left: 200px; 

    }

    .pictures a{
        text-align:justify;
        color: aliceblue;
        font-size: 20px;
        text-decoration: none;
    }

    .about{
    margin-top: 20px;
    margin: 10px;
    }
    .home{
    margin-top: 20px;
    margin: 10px;
    }
    ul{
    list-style-type: none;
    padding: 0%;
    }
    a{
    display: inline-block;
    margin-top: 10px;
    padding: 10px;
    }
   
</style>
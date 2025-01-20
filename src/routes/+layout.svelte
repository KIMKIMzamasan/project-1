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
    <p style="color: aliceblue;" >Copy Right 2025 Mazasankun</p>
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
        display: flex;
        justify-content:center;
        background-color: #8A2BE2;

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
<script>

</script>

<div class="picture">
    <img src="Me.jpg" alt="Me" style="border-radius: 50%; width: 500px;  box-shadow: 5px 5px 10px #8A2BE2 ">
</div>

    <h2>About Me</h2>

    <div class="container">

        <div class="about">
            <p>Name - Czar Von Louie Cabural</p>
            <p>Birthdate - September 24, 2002</p>
            <p>Address - National Highway, Isulan Sultan Kudarat</p>
            <p></p>
            <p style="font-weight: bold;" >Skills</p>
            <p>Experience in using Microsoft Office tools</p>
            <p>Proficient in verbal and written communications both Filipino and English</p>
            <p>Experienced in structuring and designing database schema</p>
            <p>Experienced in Web Development</p>

        </div>

        <div class="about2">
            <p>Backend Framework: Svelte (Beginner)</p>
            <p>Javascript (Beginner)</p>
            <p>dbDiagram</p>
            <p>C#</p>
            <p>Python</p>
            <p>Java</p>
            <p>MSSQL and MySQL</p>
            <p>HTML and CSS (Beginner)</p>
        </div>
       
    </div>

    <h2 style="font-weight: 300;">MEMORIES</h2>
    
    <h2>TAGISAN</h2>

    <div class="Tagisan">
       <img src="15.jpg" alt="">
         <img src="16.jpg" alt="">
            <img src="17.jpg" alt="">
            <img src="18.jpg" alt="">
            <img src="19.jpg" alt="">
            <img src="20.jpg" alt="">
            <img src="21.jpg" alt="">
            <img src="22.jpg" alt="">
            <img src="23.jpg" alt="">
            <img src="24.jpg" alt="">
            <img src="25.jpg" alt="">
            <img src="26.jpg" alt="">
            <img src="27.jpg" alt="">
            <img src="28.jpg" alt="">
            <img src="29.jpg" alt="">
    </div>


    <h2>SCHOOL</h2>


    <div class="School">
        <img src="1.jpg" alt="">
        <img src="2.jpg" alt="">
        <img src="3.jpg" alt="">
        <img src="4.jpg" alt="">
        <img src="5.jpg" alt="">
        <img src="6.jpg" alt="">
        <img src="7.jpg" alt="">
        <img src="8.jpg" alt="">
        <img src="9.jpg" alt="">
        <img src="12.jpg" alt="">
        <img src="13.jpg" alt="">
        <img src="14.jpg" alt="">

    </div>

<style>
    .about{
        text-align: center;
        display: block;
        margin: 20px auto;
        
    }

    h2{
        font-size: 50px;
        text-align: center;
        display: block;
    }

    .about p{
        text-align: justify;
        font-size: 30px;
        display: block;
        margin: 20px;
    }

    .about2{
        text-align: center;
        display: block;
        margin: 20px auto;
   
    }
    .about2 p{
        text-align: justify;
        font-size: 30px;
        display: block;
        margin: 20px;
    }

    .picture{
        display: block;
        margin: auto 1rem;
        padding: 2rem 2rem;
        text-align: center;
    }

    .container{
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-gap: 20px; 
   
    }

    .School{
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
        grid-gap: 20px;
    }

    .School img {
        width: 150px;
        height: 150px;
        object-fit: cover;
        box-shadow: 5px 5px 10px #8A2BE2;
        transition: transform 0.3s, box-shadow 0.3s;
        cursor: pointer;
    }

    .School img:hover {
        transform: scale(1.1);
        box-shadow: 10px 10px 20px #8A2BE2;
    }

    .School img:active {
        transform: scale(5);
        box-shadow: 15px 15px 30px #8A2BE2;
        z-index: 10;
        position: fixed;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%) scale(5);
    }

    .Tagisan{
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
        grid-gap: 20px;
    }

    .Tagisan img {
        width: 150px;
        height: 150px;
        object-fit: cover;
        box-shadow: 5px 5px 10px #8A2BE2;
        transition: transform 0.3s, box-shadow 0.3s;
        cursor: pointer;
    }

    .Tagisan img:hover {
        transform: scale(1.1);
        box-shadow: 10px 10px 20px #8A2BE2;
    }

    .Tagisan img:active {
        transform: scale(5);
        box-shadow: 15px 15px 30px #8A2BE2;
        z-index: 10;
        position: fixed;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%) scale(5);
    }

</style>
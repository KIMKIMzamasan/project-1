<script>

</script>
<h1>Portfolio</h1>

<div class="container">
    <div class="index">
    
        <p></p>
    
        <p>Hi, my name is Czar Von Louie Cabural, enthusiastic about technology and programming, proficient in designing database schema, and passionate about solving problems to deliver web-based solutions that efficiently streamline processes.</p>
    </div>
    
    <div class="picture">
    <img src="computer.svg" alt="computer" >
    </div>
    <div class="index">
    
        <p></p>
    
        <p>As a 4th year student, I love playing games like: League of Legends, Valorant, Terraria, Minecraft, Roblox, Tetris, Strinova, Risk of Rain 2, and Battlefield 4 - this is my stress reliever, after working on an assignment or after school I play video games to ease my self and to relax for a little bit.</p>
    </div>
    
    <div class="picture">
    <img src="game.svg" alt="game controller">
    </div>

</div>

<div class="description">
    <p>There are hobbies I am really good at, and I used them to compete in school competitions and outside of school.</p>
</div>

<div class="container_2">
    <div class="index">
    
        <p></p>
    
        <p>I also play chess, this is my favorite board games to play when I was a kid and up until now, this game helps me to built up a strategic mind and strong critical decision skills to later on be used as I progress in age.I have competed multiple contest about this game, gaining valuable experience that has further enhanced my skills and passion for chess.</p>
    </div>
    
    <div class="picture">
    <img src="chess.svg" alt="chess piece" >
    </div>
    <div class="index">
    
        <p></p>
    
        <p>I also like to sing, this is a talent I've discovered later on that I have but doesn't notice while I was younger. I love to sing everytime, it doesn't matter if it's in the bathrooom, kitchen, room, or outside. I've honed this talent and joing singing contest in school and outside school.</p>
    </div>
    
    <div class="picture">
    <img src="microphone.svg" alt="microphone">
    </div>
</div>

<style>
h1 {
    text-align: center;
    display: block;
    margin: 20px auto;
    font-size: 100px;
    
}
.index p {
    text-align: justify;
    font-size: 30px;
    display: block;
    margin: 20px;
   
}

.index {
  display: block;
  margin: auto 1rem;
  padding: 2rem 2rem;
  text-align: center;
  
}

.picture {
  display: block;

  margin: auto 1rem;
  padding: 2rem 2rem;
  text-align: center;
}

.picture img{
    fill: #8A2BE2;
    width: 300px;
}

/* .picture p {
    text-align: justify;
    display: block;
    margin: 20px;
} */

.description{
    display: block; 
    grid-template-columns: 1fr 1fr; 
    grid-gap: 20px; 
    width: 100% auto; 

}

.description p{
    text-align: justify;
    font-size: 30px;
    display: block;
    margin: 20px;
    padding: 2rem 2rem;
}

.container {
    display: grid; 
    grid-template-columns: 1fr 1fr; 
    grid-gap: 20px;  

}

.container_2 {
    display: grid; 
    grid-template-columns: 1fr 1fr; 
    grid-gap: 20px;  

}

@media (max-width: 430px){
    h1 {
    text-align: center;
    display: block;
    margin: 20px auto;
    font-size: 100px;
    }

    .container{
    display: block; 
    grid-template-columns: 1fr 1fr; 
    grid-gap: 20px; 
    width: 50% auto; 
    }

    .container_2{
    display: block; 
    grid-template-columns: 1fr 1fr; 
    grid-gap: 20px; 
    width: 50% auto; 
    }

    .picture{
    display: block;
    margin: 1rem;
    padding: 2rem 2rem;
    text-align: center;
    }

    .picture img{
        width: 200px;
    }
}

</style>
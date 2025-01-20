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
    
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat, quasi expedita? Mollitia eveniet, a natus, impedit molestias et tempore, corrupti architecto deleniti officiis rem minus eaque vel distinctio dignissimos quaerat.</p>
    </div>
    
    <div class="picture">
    <img src="game.svg" alt="game controller">
    </div>

</div>

<div class="description">
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Veniam odio tenetur reprehenderit in. Ipsam nostrum illum consectetur! Ab ratione doloremque velit quaerat ipsum amet incidunt officiis, eum quo voluptate doloribus?</p>
</div>

<div class="container_2">
    <div class="index">
    
        <p></p>
    
        <p>Hi, my name is Czar Von Louie Cabural, enthusiastic about technology and programming, proficient in designing database schema, and passionate about solving problems to deliver web-based solutions that efficiently streamline processes.</p>
    </div>
    
    <div class="picture">
    <img src="chess.svg" alt="chess piece" >
    </div>
    <div class="index">
    
        <p></p>
    
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat, quasi expedita? Mollitia eveniet, a natus, impedit molestias et tempore, corrupti architecto deleniti officiis rem minus eaque vel distinctio dignissimos quaerat.</p>
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
<svelte:head>
    <title>Andor - cast page</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@200..700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap" rel="stylesheet">
</svelte:head>

        <div class="row1">
            <div class="col1">
                <img src="img/resistance.jpg" alt="image of the Resistance">
            </div>
            <div class="col1">
                <p>
                    Andor serves as a prequel to Rogue One: A Star Wars Story, following the character of Cassian Andor long before he meets Jyn Erso and steals the plans for the Death Star. Taking place five years before the events of Rogue One, it follows a cast of characters as they slowly come together to form what will become the oﬃcial Rebel Alliance against the Galactic Empire.
                </p>
            </div>
        </div>
        <div class="row2">
            <div class="col2">
                <img src="img/scene1.jpg" alt="image of a scene from the show">
            </div>
            <div class="col2">
                <img src="img/scene2.jpg" alt="image of a scene from the show">
            </div>
            <div class="col2">
                <img src="img/scene3.jpg" alt="image of a scene from the show">
            </div>
        </div>
        
        <div class="row3">
            <div class ="col3">
                <img src="img/Cassian.jpg" alt="image of Cassian">
            </div>
            <div class ="col3">
                <h3>CASSIAN</h3>
                <p>
                    Cassian Andor, lives on the rough-and-tumble planet of Ferrix, and is known as a scoundrel to the town: a wastrel, a swindler, and a guy who doesn't always make the best decisions. When he is involved in a crime one night, Cassian Andor gets on the Empire's radar. But someone is soon to oﬀer him a chance to do something more with his life.
                </p>    
            </div>
            <div class ="col3">
                <h3>LUTHEN RAEL</h3>
                <p>
                    On the surface, the wily Luthen Rael acts as a collector and something of a black market dealer. His real aim, however, is to quietly build the seeds of rebellion. His meeting with Cassian Andor has changed both their lives, and potentially the fate of the galaxy itself.
                </p>
            </div>
            <div class ="col3">
                <img src="img/Rael.jpg" alt="image of Luthen Rael">
            </div>
        </div>
        <div class="row4">
            <div class ="col3">
                <h3>MAARVA</h3>
                <p>
                    Maarva is a wily ship raider who adopted Cassian when he was young and taught him all she knows. While she doesn't condone Cassian's shadier activities, she loves him dearly. As a former leader of Star Wars' proto-Rebellion, Maarva has become part of the new uprising as her son gets drawn into events, despite her declining health.
                </p>
            </div>
            <div class ="col3">
                <img src="img/Maarva.jpg" alt="image of Maarva">
            </div>
            <div class ="col3">
                <img src="img/Mon.jpg" alt="image of Mon Mothma">
            </div>
            <div class ="col3">
                <h3>MON MOTHMA</h3>
                <p>
                    At this point in the Star Wars timeline, Mon Mothma is in a very dangerous and diﬃcult position. As a savvy politician in the Imperial Senate, Mon Mothma is also one of the most important architects of what will become the Rebellion. Along with Luthen Rael, she plays a key role in helping to turn the tide against the Imperial regime.
                </p>
            </div>
       </div> 
    
    <style>
        .row1{
    display: flex;
    padding: 1rem;
}

.row1 img {
    width: 100%;
    border: 5px solid #b4681c;
}


.row2{
    display: flex;
    padding: 1rem;
}

.row2 img {
    width: 100%;
    border: 5px solid #b4681c;
}

.row3{
    display: flex;
}

.row3 img {
    width: 100%;
    border: 5px solid #b4681c;
}

.row4{
    display: flex;
}

.row4 img{
    width: 100%;
    border: 5px solid #b4681c;
}

.col1{
    width: 50%;
    text-align: justify;
    font-size: 30px;
}
.col1 p{
    font-family: "Oswald";
    font-weight: 400;
    padding-left: 50px;
}

.col2{
    width: 33%;
    padding: 0.2rem;
}

.col3{
    width: 25%;
    padding: 1rem;
    text-align: justify;
}

.col3 p{
    font-family: "Rationale";
    font-size: 20px
}

.col3 h3{
    font-family: "Lato", sans-serif;
    font-weight: 900;
    border-top: 5px solid #b4681c;
    font-size: 30px;
}

.col3 p, .col3 h3{
    padding: 0 1.5rem;
}
    </style>
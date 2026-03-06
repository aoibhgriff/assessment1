<script>
  import { onMount } from "svelte";

  let characters = [];

  onMount(async () => {
    const res = await fetch("https://akabab.github.io/starwars-api/api/all.json");
    const data = await res.json();
    characters = data.filter(c => c.image).slice(0, 19);
  });
</script>

<svelte:head>
<title>Andor - merch page</title> 
<link rel="preconnect" href="https://fonts.googleapis.com"> 
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> 
<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@200..700&display=swap" rel="stylesheet"> 
<link href="https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap" rel="stylesheet"> 
<link href="https://fonts.googleapis.com/css2?family=Rationale&display=swap" rel="stylesheet"> 
</svelte:head>

<main>
<h1>Buy Star Wars Figures of your favourite characters!</h1>
<h2>Only $15 per figure!</h2>

<div id="show">
  {#each characters as char}
    <div class="showmerch">
      <h3>{char.name} figure</h3>
      <img src={char.image} alt={char.name}>
      <input type="button" value="Add to cart">
    </div>
  {/each}
</div>

<form>
  <fieldset>
    <legend>Please enter your details: </legend>
    <label for="fname">Full name: </label>
    <input type="text" id="fname"><br><br>

    <label for="mail">Email: </label>
    <input type="email" id="mail"><br><br>

    <label for="add">Address: </label>
    <input type="text" id="add"><br><br>

    <input type="submit" value="Submit">
  </fieldset>
</form>
</main>
<style>
        h1  {
            font-family: "Lato";
            text-align: center;
            font-size: 2.5rem;
        }
        h2{
            font-family: "Oswald";
            text-align: center;
            font-size: 1.8rem;
        }
        .showmerch {
            width: 180px;
            background-color: black;
            border: 3px solid #b4681c;
            border-radius: 10px;
            text-align: center;
            padding: 10px;
        }
        
        #show {
            max-width: 1200px;
            margin: 30px auto;
            display: flex;
            flex-wrap: wrap;
            justify-content: center; 
            padding: 20px;
        }

        #show img {
            width: 150px;
            height: auto;
            padding: 1rem;
        }
        .showmerch input[type="button"] {
            color: white;
            background-color: #b4681c;
            border: none;
            padding: 5px 10px;
            cursor: pointer;
        }
        
        form{
            display: block;
            text-align: center;
            font-family: "Rationale";
        }
        form input[type="submit"]{
            background-color: #b4681c;
            cursor: pointer;
            padding: 5px 10px;
        }
        fieldset {
            background-color: #932727;
            color: white;
            border: 2px solid #b4681c;
            border-radius: 5px;
            padding: 1rem;
            margin: 1rem auto;
        }
</style>
        
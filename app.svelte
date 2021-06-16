<script>
    let firstname ="";
	let src ="favicon.png"
    let lastname = "";
	
	
	</script>

<main>
    <h1>hello!this is {firstname}{lastname}!!!!</h1>
    <label for="firstname">FIRST NAME</label>
	<input type="text" bind:value={firstname}>
	<label for="lastname">LAST NAME</label>
    <input type="text" bind:value={lastname}>


	<img src ={src} alt="svelte logo">

</main>

<style>
	main {
		display: flex;
		flex-direction: column;
        align-items: center;
	}
    h1{
        font-style: italic;
        font-weight: bold;
        font-size: xx-large;
        text-align: center;
	}
</style>

<script>
	
    import { goto } from '$app/navigation';

    function routeToPage(route) {
        goto(route);
    }
	/*
	from belgium
	why do i love/like front end
	maybe: button that leads to projects file. "Check my latest work"
	*/
</script>

<main>
	<div class="title">
		<p>I'm a Flemish self-thaught</p>
		<h1>Front-end</h1>
		<h2>Developer</h2>
	</div>
	<div class="content">
		<p>I love front-end just because <br>of the freedom it gives <br>you to make any design you want.</p>
		<div class="button-container">
			<button class="btn-projects">
			  Check my latest work!
			</button>
			<button class="btn-about">
			  About me
			</button>
		  </div>		  
	</div>
	<div class="box-content">
		<h1 style="box-shadow: none;">???</h1>
	</div>
	
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	.title p{
		color: black;
		font-size: 1.5em;
		font-weight: 100;
		font-family: monospace;
		margin-top: 3rem;
		margin-bottom: 0;
	}

	.title h1 {
		color: black;
		text-transform: uppercase;
		font-size: 5em;
		font-weight: 100;
		margin-top: 0;
		margin-bottom: 0;
		text-shadow: 5px 10px 8px grey;
		font-family: monospace;
		box-shadow: 0 0;
	}

	.title h2{
		color: black;
		text-transform: uppercase;
		font-size: 4.5em;
		font-weight: 100;
		margin-top: 0;
		text-shadow: 5px 10px 8px grey;
		font-family: monospace;
	}

	.title{
		box-shadow: 0 5px;
	}

	.content{
		margin-top: 10em;
	}

	.button-container {
  		display: flex;
  		flex-direction: grid;
  		align-items: flex-start;
  		margin-left: 11em;
	}

	.content p{
		font-family: monospace;
		font-size: 1.5em;
		margin-top: 7rem;
		color: black;
		display: flex;
		align-content: flex-start;
		justify-content: left;
		margin-left: 10em;
	}

	.btn-projects{
		height: fit-content;
		font-size: 1.5em;
		font-family: monospace;
		background-color: burlywood;
		color: white;
		box-shadow: 5px 5px black;
		cursor: pointer;
		transition: 500ms;
		border: 2px solid black;
	}

	.btn-projects:hover{
		background-color: black;
		color: white;
		box-shadow: 5px 5px burlywood;
		transition: 500ms;
		border: 2px solid burlywood;
	}

	.btn-about{
		height: fit-content;
		font-size: 1.5em;
		font-family: monospace;
		background-color: #3eaf76;
		color: white;
		box-shadow: 5px 5px black;
		cursor: pointer;
		transition: 500ms;
		border: 2px solid black;
		margin-left: 1em;
	}

	.btn-about:hover{
		background-color: black;
		color: white;
		box-shadow: 5px 5px #3eaf76;
		transition: 500ms;
		border: 2px solid #3eaf76;
	}

	.box-content {
  		border: 4px solid black;
  		border-radius: 5px;
  		height: 350px;
  		width: 400px;
  		float: right;
		margin-right: 12em;
  		margin-top: -13em;
	}



	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>

<nav class="nav-bar">
    <a class="objects" href="/">home</a>
    <a class="objects" href="/about">about me</a>
    <a class="objects" href="/projects">projects</a>
    <a class="objects" href="/contact">contact me</a>
</nav>

<style>
    .nav-bar {
        border: 1px solid black;
        border-radius: 10px;
        box-shadow: 5px 5px;
        width: fit-content;
        padding: 1em;
        position: fixed;
        top: 2%; 
        right: 1%; 
        display: flex; 
        flex-direction: row; 
        justify-content: flex-start; 
    }

    .objects {
		font-family: monospace;
        padding: 0.7em;
        font-size: large;
        text-decoration: none;
        color: black;
        transition: 400ms;
        border-radius: 5px;
    }

    .objects:hover{
        text-decoration: solid;
        background-color: black;
        color: white;
        transition: 500ms;
    }
</style>

<slot />
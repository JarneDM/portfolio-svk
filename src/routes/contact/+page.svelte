<script>
</script>

<main>
    <h1>Contact</h1>
    <div class="outer-container">
        <div class="container">
            <input type="text" class="name" placeholder="Full Name">
            <input type="text" class="email" placeholder="E-mail">
            <textarea style="resize: none;" name="message" class="message" placeholder="Message..." cols="30" rows="10"></textarea>
            <input type="submit" class="submit-btn" value="Submit">
        </div>
    </div>
</main>

<style>
    main {
        text-align: center;
        padding: 1em;
        max-width: 100%;
        margin: 0;
        font-family: monospace;
    }

    .outer-container{
        display: flex;
	    justify-content: center;
	    align-items: center;
        margin-top: 3em;
    }

    .container{
        border: 1px solid black;
        border-radius: 5px;
        width: 850px;
        height: 480px;
        margin: 0;
    }

    .name{
        height: 2em;
        width: 30em;
        border-radius: 5px;
        margin-top: 1.5em;
        margin-bottom: 1.5em;
        border: 1px solid black;
    }

    .email{
        margin-left: 5px;
        height: 2em;
        width: 30em;
        border-radius: 5px;
        border: 1px solid black;
    }

    .message{
        height: 25em;
        width: 61em;
        border-radius: 5px;
    }

    .submit-btn{
        height: 3em;
        width: 9em;
        border-radius: 5px;
        background-color: burlywood;
        color: black;
        box-shadow: 5px 5px black;
        font-size: large;
        font-family: monospace;
        margin-top: 5px;
        transition: 500ms;
    }

    .submit-btn:hover{
        cursor: pointer;
        background-color: black;
        color: white;
        box-shadow: 5px 5px burlywood;
        transition: 500ms;
    }
</style>
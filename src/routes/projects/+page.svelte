<main>
    <div class="title-projects">
        <h1>Projects</h1>
    </div>
    <div class="content-projects">
        <div class="project first">
            <div class="front-side">
                <h1 style="font-size: 3em; margin-top: 0.5em;">Quote generator</h1>
                <hr style="background-color: black; height:2px;">
            </div>
            <div class="back-side">
                <h1 style="font-size: 3em; margin-top: 0.5em; color:white;">Quote generator</h1>
                <hr style="background-color: white; height:2px;">
                <p style="color: white; font-size: larger; font-family:monospace;">
                    The quote generator generates quotes like you guessed. <br>The quotes are mostly from historical figures <br>like Albert Einstein, Socrates, Van Gogh, ... <br>You can visit the quote generator by <br>clicking <a style="color: white;" target="_blank" href="https://quote-generator-jarne.vercel.app/">here!</a>
                </p>
            </div>
        </div>
        <div class="project">
            <div class="front-side">
                <h1 style="font-size: 3em; margin-top: 0.5em;">Front Side</h1>
                <hr style="background-color: black; height:2px;">
            </div>
            <div class="back-side">
                <h1 style="color: white; font-size: larger;">Backs Side</h1>
            </div>
        </div>
        <div class="project">
            <div class="front-side">
                <h1 style="font-size: 3em; margin-top: 0.5em;">Front Side</h1>
                <hr style="background-color: black; height:2px;">
            </div>
            <div class="back-side">
                <h1 style="color: white; font-size: larger;">Backs Side</h1>
            </div>
        </div>
    </div>
</main>

<style>
    main {
        text-align: center;
        padding: 1em;
        max-width: 100%;
        margin: 0;
    }

    .title-projects h1 {
        color: black;
        text-transform: uppercase;
        font-size: 5em;
        font-weight: 100;
        margin-bottom: 0;
        font-family: monospace;
    }

    .content-projects {
        margin-top: 2em;
        display: flex;
        justify-content: flex-start;
        gap: 5em;
        flex-wrap: wrap;
    }

    .first{
        margin-left: 8.5em;
    }

    .project {
        height: 450px;
        width: 350px;
        border: 3px solid black;
        border-radius: 15px;
        transform-style: preserve-3d;
        transition: all 1s ease;
    }

    .front-side{
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border-radius: 10px;
        backface-visibility: hidden;
        overflow: hidden;
        background: beige;
        color: #000;
    }

    .back-side{
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border-radius: 10px;
        backface-visibility: hidden;
        overflow: hidden;
        background: black;
        color: white;
        text-align: center;
        transform: rotateY(180deg);
    }

    

    .project:hover{
        transform: rotateY(180deg);
    }
</style>

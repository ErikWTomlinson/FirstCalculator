<h1>My First Calculator! &#128562; &#128563;</h1>
<div id="calculator">
    <input type="text" style="height: 5vh" class="input-bar">
    <div class="grid-container">
        <button class="grid-item">1</button>
        <button class="grid-item">2</button>
        <button class="grid-item">3</button>
        <button class="grid-item">4</button>
        <button class="grid-item">5</button>
        <button class="grid-item">6</button>
        <button class="grid-item">7</button>
        <button class="grid-item">8</button>
        <button class="grid-item">9</button>
        <button class="grid-item">+</button>
        <button class="grid-item">-</button>
        <button class="grid-item">x</button>
        <button class="grid-item">/</button>
        <button class="grid-item">&leftarrow;</button>
        <button class="grid-item">AC</button>
    </div>
</div>

<style>
    h1{
        margin-top: 5vh;
        text-align: center;
        font-size: 50px;
    }
    #calculator{
        max-width: 50vw;
        margin: auto;
        margin-top: 5vh;
    }
    .input-bar{
        border-width: 2px;
        font-size: 20px;
        text-align: right;
        box-sizing: border-box;
        width:100%;
    }
    .grid-container{
        display:grid;
        max-width: 50vw;
        grid-template-columns: auto auto auto;     
    }
    .grid-item:active{
        background-color: lightgray;
    }
    .grid-item{
        background-color: white;
        border-width: 2px;
        font-size: 50px;
        font-family: 'Times New Roman', Times, serif;
    }
</style>

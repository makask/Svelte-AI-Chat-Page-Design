<script>
	
</script>


<div class="main">
	<div class="main-buttons">
        <button class="gpt-btn active"><i class="fa-solid fa-wand-magic-sparkles gradient" style="color: #5d3aed;"></i>&nbsp;GPT-3.5</button>
        <button class="gpt-btn inactive"><i class="fa-solid fa-bolt gradient" style="color: #74C0FC;"></i>&nbsp;GPT-4</button>
    </div>
    <div class="div-dropdown">
        <select class="plugins-select" name="cars" id="cars">
            <option>No plugins enabled</option>
            <option>Plugin 1.0</option>
            <option>Plugin 2.0</option>
          </select>
    </div>
    <div class="center-main">
        <img src="images/logo.jpg" alt="userimage"/>
    </div>
    <div class="center-input">
        <input class="input-message" type="text" placeholder="Send a message">
        <button class="btn-submit-message">Submit</button>
    </div>
    <div>
        <p class="txt-info">Free Research Preview. ChatGPT may produce inaccurate information about people, places, of facts.<a class="version-info" href="/">ChatGPTMay12Version</a></p>
    </div>
</div>

<style>
	.main{
        display: flex;
        flex-direction: column;
    }
    .main-buttons{
        display: flex;
        justify-content: center;
        gap:1rem;
    }
    .gpt-btn{
        padding: 0.5rem;
        width: 150px;
        background-color: #ffffff;
        border-radius: 10px;
        font-weight: bold;
        border: none;
    }
    .active{
        box-shadow: 10px 0 20px 0 rgba(211, 211, 211, 0.5);
    }
    .inactive{
        opacity: 0.3;
    }
    .plugins-select{
        border: none;
        font-size: 14px;
        color: gray;
    }
    .center-main{
        background-image: url({imageUrl});
    }
    .center-input{
        display:flex;
        align-items: center;
        justify-content: center;
        gap:0.5rem;
    }
    .btn-submit-message{
        background: linear-gradient(to top, #4322c9, #8868ee); 
        color: white;
        height: 50px;
        width: 180px;
        border-radius: 20px;
        font-size: 14px;
    }
    .txt-info{
        font-size: 12px;
    }
    .version-info{
        text-decoration: underline;
    }
    .input-message{
        color:gray;
        font-size: 14px;
        width: 700px;
        padding: 12px;
        border-radius: 12px;
    }
    .gradient{
        border-radius: 50%;
        background: linear-gradient(to top, #ccccff, #f5f5ff);
        padding: 12px;
    }
</style>
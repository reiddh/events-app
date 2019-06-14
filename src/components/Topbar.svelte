<style>
    .topbar{
        background: #fff;
        width:100vw;
        box-shadow:0px 2px 2px #ccc;    
        position: fixed;
        font-weight: bold;
        font-size:16px;  
        display:flex;
    }

    button{
        width:56px;
        height:56px;
        background-color:#fff;
        border:none;        
        margin:0px;
        padding:0px;
        margin-top:0px;
        flex:1;
    }
    button.title{
        text-align: center;
        flex:4;
        text-align:left;
        font-weight:bold;
    }
    svg{
        display: block;
        margin:auto;
    }
</style>
<div class="topbar">
    <button class="iconButton">
    <span>
    <svg 
        xmlns="http://www.w3.org/2000/svg" 
        width="24" 
        height="24" 
        viewBox="0 0 24 24">
            <path d="M17 12h-5v5h5v-5zM16 1v2H8V1H6v2H5c-1.11 
            0-1.99.9-1.99 2L3 19c0 1.1.89 2 2 2h14c1.1 0 2-.9 
            2-2V5c0-1.1-.9-2-2-2h-1V1h-2zm3 18H5V8h14v11z"/>
            <path d="M0 0h24v24H0z" fill="none"/>
    </svg>
    </span>        
    </button>
    <button class="title">
        <span>Events</span>
    </button>
    <button>
        <i> 
        
        <svg 
            xmlns="http://www.w3.org/2000/svg" 
            width="24" 
            height="24" 
            viewBox="0 0 24 24">
                <path d="M15.5 14h-.79l-.28-.27C15.41 12.59 16 11.11 16 
                9.5 16 5.91 13.09 3 9.5 3S3 5.91 3 9.5 5.91 16 9.5 16c1.61 
                0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6
                0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"/>                
        </svg>
        </i>
    </button>
</div>
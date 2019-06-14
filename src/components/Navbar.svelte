<script>
    const doSomething = (event)=>{
        event.stopPropagation();
        console.log(event)
    }

      
    
</script>

<style>
    
    .container{
        height:56px;
        width: 100vw;
        box-shadow: 0px -3px 5px rgba(44, 44, 44, 0.1);
        position:fixed;
        bottom:0px;
        display:flex;
        align-items:stretch;
    }

    button{
        height: 56px;
        font-size: 10px;
        font-weight:bold;
        width:auto;
        flex:1;
        background:#fff;
        border:0px;
        cursor:pointer;
        z-index:1
    }
    button span{
        display:block;
    }

</style>
<div class="container">
    <button on:click={doSomething}>
        <span>
            <svg 
                xmlns="http://www.w3.org/2000/svg" 
                width="24" 
                height="24" 
                viewBox="0 0 24 24">
                    <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z"/>
                    <path d="M0 0h24v24H0z" fill="none"/>
            </svg>
        </span>
        <span>
            Home
        </span>
    </button>
    <button type = submit on:click={doSomething}>
        <span>
            <svg 
                xmlns="http://www.w3.org/2000/svg" 
                width="24" 
                height="24" 
                viewBox="0 0 24 24">
                <path d="M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 
                        10C17.52 22 22 17.52 22 12S17.52 2 11.99 
                        2zM12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8 8 
                        3.58 8 8-3.58 8-8 8z"/>
                <path d="M0 0h24v24H0z" fill="none"/>
                <path d="M12.5 7H11v6l5.25 3.15.75-1.23-4.5-2.67z"/>
            </svg>
        </span>
        <span>
            Schedule
        </span>
    </button>
    <button type = submit on:click={doSomething}>
        <span>
            <svg 
                xmlns="http://www.w3.org/2000/svg" 
                width="24" 
                height="24" 
                viewBox="0 0 24 24">
                    <path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 
                            13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 
                            9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 
                            2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/>
                    <path d="M0 0h24v24H0z" fill="none"/>
            </svg>
        </span>
        <span>
            Locatiion
        </span>
    </button>
    <button type = submit on:click={doSomething}>
        <span>
            <svg 
                xmlns="http://www.w3.org/2000/svg" 
                width="24" 
                height="24" 
                viewBox="0 0 24 24">
                    <path d="M0 0h24v24H0z" fill="none"/>
                    <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 
                            10 10-4.48 10-10S17.52 2 12 2zm1 
                            15h-2v-6h2v6zm0-8h-2V7h2v2z"/>
            </svg>
        </span>
        <span>
            Info
        </span>
    </button>
    <button type = submit on:click={doSomething}>
        <span>
            <svg 
            xmlns="http://www.w3.org/2000/svg" 
            width="24" 
            height="24" 
            viewBox="0 0 24 24">
                <path d="M0 0h24v24H0z" fill="none"/>
                <path d="M22 16V4c0-1.1-.9-2-2-2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 
                        2h12c1.1 0 2-.9 2-2zm-11-4l2.03 2.71L16 11l4 5H8l3-4zM2 
                        6v14c0 1.1.9 2 2 2h14v-2H4V6H2z"/>
            </svg>        
        </span>
        <span>
            Gallery
        </span>
    </button>

</div>
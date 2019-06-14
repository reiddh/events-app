<script>
    import {Events} from '../Store/index.js'
    import Topbar from '../components/Topbar.svelte'

    console.log(Events.length)


   // num_events.appendChild(num_events_text)
</script>
<style>

    .event_container{
        background:#ccc;        
        position: relative;
        z-index: -1;
       
    }
    .event_container::before{
        content:'';
        height:56px;
        margin: 0px;
        display:block;
    }

    .tabs{
         display:flex;
    }

    button {
        text-decoration: none;
        color:black;
        height:60px;
        padding:0px;
        margin:0px;
        flex:1;
        background: #fff;
        border: 0px;
    }




</style>
<Topbar />

<div class="event_container">
    <div class="tabs">
        <button>Upcoming</button>
        <button>Attending</button>
        <button>Past</button>
    </div>
    <div class="item_count">   
        Events found ({Events.length})
    </div>
</div>


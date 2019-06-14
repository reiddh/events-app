<script>
	import Navbar from './components/navbar.svelte'
	import {Router,Route} from 'svelte-routing'
	
	import Events from './Routes/Events.svelte'
	import Event from './Routes/Event.svelte'

</script>

<Router>
	<Route path="/" component={Events} />
	<Route path="/Event" component={Event}/>
</Router>



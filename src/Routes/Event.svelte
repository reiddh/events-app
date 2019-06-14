<script>
	import Navbar from '../components/navbar.svelte'
	import {Router,Route} from 'svelte-routing'
	
	import Events from './Events.svelte'




</script>
<Router>
	<Route path="/" component={Events} />
</Router>
<Navbar />
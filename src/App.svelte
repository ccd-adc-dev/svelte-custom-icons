<script>
	import Icon from './components/icons/Icon.svelte'
	import Icons from './components/icons/Icons.svelte'
	export let name;
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Hello {name}!</h1>
<Icons/>
<Icon colorLinea="red" colorRelleno="red" name="link"></Icon>
<Icon colorLinea="blue" colorRelleno="blue" size="50" name="close"></Icon>
<Icon colorLinea="green" colorRelleno="green" size="80" name="download"></Icon>
<Icon colorLinea="orange" colorRelleno="orange" size="100" name="github"></Icon>

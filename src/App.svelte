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
<Icon name="link"></Icon>
<Icon size="50" name="close"></Icon>
<Icon size="80" name="download"></Icon>
<Icon size="100" name="github"></Icon>

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

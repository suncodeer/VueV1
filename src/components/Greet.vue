<template>
	<div id="Greet">
		<h6> I am the component from greet.vue file </h6>
		<ol>
			<li>List One</li>
			<li>List Two</li>
			<li>{{message}}</li>
		</ol>
	</div>
</template>

<script >
	module.exports = {
		name: 'Greet',
		data: function () {
			return {
				'message': 'Hello single Vue File world'
			}
		}
	}
</script>
<style>

	ul h6 {
		padding: 0px;
		margin: 0px
	}
</style>
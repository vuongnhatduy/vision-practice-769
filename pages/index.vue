<template>
	<div>
		<h1>
 			This is search book
 		</h1>
 		<v-text-field class="search-text-field" label="Search Book"/>
		<div id="foundBook" class="found-book">
			<v-row>
				Book 1
			</v-row>
			<v-row>
				Book 2
			</v-row>
		</div>
 	</div>
</template>

<script>

export default {

}
</script>
<style>
	.search-text-field{
		width: 80%;
		align-self: center;
	}
	.found-book {
		width: 80%;
	}
</style>

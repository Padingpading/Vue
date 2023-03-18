<template>
    <div class="demo">
					<h3>学生名称：{{name}}</h3>
					<h3>学生年龄：{{age}}</h3>
  			</div>
</template>

<script>
   export default {
		name:'School',
		data() {
			return {
				name: 'sx',
				age: 18
			}
		}
	}
</script>

<style>
	.demo{
		background-color:orange;
	}
</style>


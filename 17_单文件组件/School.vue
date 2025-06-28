<template>
    <div class="demo">
					<h3>学校名称：{{schoolName}}</h3>
					<h3>学校地址：{{address}}</h3>
					<button @click="showName">点我提示学校名</button>	
  			</div>
</template>

<script>
   export default {
		name:'School',
		data() {
			return {
				schoolName: '尚硅谷',
				address: '北京昌平'
			}
		},
		methods: {
			showName() {
				alert(this.schoolName)
			}
		}
	}
</script>

<style>
	.demo{
		background-color:orange;
	}
</style>


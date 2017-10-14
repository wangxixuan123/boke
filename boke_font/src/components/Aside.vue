<template>
	<div class="right">
		<div class="search">
			<h3>查找文章</h3>
			<el-input
			  placeholder="文章标题"
			  icon="search"
			  v-model="input2"
			  :on-icon-click="handleIconClick" style="margin-top:20px;">
			</el-input>
			
		</div>
	</div>
</template>
<script>
	export default {
	  data() {
	    return {
	      input2: ''
	    }
	  },
	  methods: {
	    handleIconClick(ev) {
	      console.log(ev);
	    }
	  }
	}
</script>
<style>
	.right{
	  width:320px;
	  height:500px;
	  float:left;
	  margin-left:30px;
	  color:#999;
	  border:1px solid #999;
	  border-radius:10px;
	}
	.search{
		width:300px;
		margin:auto;
		text-align: center;
	}
	.search h3{
		padding:20px 20px 0px 0px;
	}
</style>
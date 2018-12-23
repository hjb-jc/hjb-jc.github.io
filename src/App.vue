<template>
	<div id="app">

		<el-container>
			<el-aside width="200px"><Portrait></Portrait></el-aside>
			<el-container>
				
				<el-main>
					<MainPage></MainPage>
				</el-main>
			</el-container>
		</el-container>
		
	</div>
</template>

<script>
	import MainPage from './components/MainPage.vue'
	import Portrait from './components/Portrait.vue'
	export default {
		name: 'app',
		components: {
			MainPage : MainPage,
			Portrait : Portrait
			
		}
	}
</script>

<style>
	#app {
		font-family: 'Avenir', Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
		margin: auto;
	}

	.el-aside {
		background-color: #D3DCE6;
		color: #333;
		text-align: center;
	}

	.el-main {
		background-color: #E9EEF3;
		color: #333;
		text-align: center;
		overflow: hidden；
	}

	body>.el-container {
		margin-bottom: 40px;
	}

	.el-container:nth-child(5) .el-aside,
	.el-container:nth-child(6) .el-aside {
	}

	.el-container:nth-child(7) .el-aside {
		line-height: 320px;
	}
</style>

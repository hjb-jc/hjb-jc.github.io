<template>
	
		<!-- <MainPage></MainPage> -->
			<div id="centen">
				<div id="flex-centainer">
					
					<div >
						<div style="display: flex; font-weight:bold;">基本资料</div>
						<img style="width: 40%; height: 40%;" src="./assets/微信图片_20181111155008.jpg">
						<div style="display: flex; width: 60%; height: 100%;">求职意向：java开发岗位</div>	
					</div>
					
					<div class="flex-item" id="flex">
						<ul type="none" class="ul-one">
							<li>姓名：黄京霸</li>
							<li>性别：男</li>
							<li>民族：壮族</li>
							<li>学历：专科</li>
							<li>生日：1997-12-06</li>
						</ul>
					</div>
	
					<div class="raw-item" id="raw">
						<ul type="none" class="ul-one">
							<li>专业：软件工程</li>
							<li>地址：现居珠海</li>
							<li>邮政：xxxxx</li>
							<li>电子邮件：648178100@qq.com</li>
							<li>联系电话：13543050567</li>
						</ul>
					</div>
				
	
				</div>
	
			</div>
			<hr style="border:1px dashed #000; height:1px; width: 70%;">
			
			<div id="centen-two">
				<div>
					<div>
						<div style="text-align: left;font-weight:bold;">教育背景</div>
						<ul>
							<li>1999.9-2000.09 南方it学院qqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqq</li>
							<li>qwqqqqqq1999.9-2000.09 暨南大学</li>
						</ul>
					</div>
	
					<div>
						<div style="text-align: left;font-weight:bold;">职业技能</div>
						<ul>
							<li>qwwwwwwwwwwwwww1999.9-2000.09 南方it学院</li>
							<li>qwwwwwwwwwwwqqqqq1999.9-2000.09 暨南大学</li>
						</ul>
					</div>
	
					<div>
						<div style="text-align: left;  font-weight:bold;">项目</div>
						<ul>
							<li>1999.9-2000.09 南方it学院</li>
							<li>1999.9-2000.09 暨南大学</li>
						</ul>
					</div>
	
					<div>
						<div style="text-align: left; font-weight:bold;">自我评价</div>
						<ul style="list-style: lower-alpha; ">
							<li style="width: 100%; list-style-position: inside;">
								1999.9-2000.09 南方it学院
								</li>
							<li>1999.9-2000.09 暨南大学</li>
						</ul>
					</div>
	
				</div>
			</div>
	
</template>

<script>
	export default {
		data() {
			return {
				
			};
		}
	}
</script>

<style>
	#centen {
			border: 1px solid yellow;
			width: 70%;
			height: 100%;
			margin: auto;
			display: flex;
			font-family: NSimSun;
			font-size: 1.3em;
			text-indent: calc();
			flex: 1 1 auto;
		}
	
		#centen-two {
			border: 1px solid yellow;
			width: 70%;
			height: 100%;
			margin: auto;
			display: flex;
			font-family: NSimSun;
			font-size: 1.3em;
		}
		
			#centen-two > ul {
				float: left;
			margin:0px;
			list-style: lower-alpha;
		}
		
		#centen-two > ul >li {
			margin: 0em;
			width:100%;
			float: left;
			list-style-type: square;
			
		}
	
		#flex-centainer {
			display: flex;
			flex-direction: row;
			text-align: left;
			float: left;
		}
	
		#flex-centainer>.flex-item {
			flex: auto;
			margin: 0.6em;
			border: 1px solid yellow;
			display: flex;
			width: 50%;
			height: 100%;
		}
	
		#flex-centainer>.raw-item {
			flex: auto;
			margin: 0.6em;
			border: 1px solid red;
			display: flex;
			width: 50%;
			height: 100%;
			align-items: flex-start; 
		}
		
		.ul-one > li{
			margin: 0.3em;
		}
	
</style>

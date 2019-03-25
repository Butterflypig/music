<template>
    <div>
        <footer class="foot">
          <div class="footBar">
            <div>
              <em>发现</em>
            </div>
            <div>
              <em>正在播放</em>
            </div>
            <div>
              <em>音乐圈</em>
            </div>
            <div>
              <em>个人中心</em>
            </div>
          </div>
        </footer>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.foot{
	color: #fff;
	width: 100%;
	position: fixed;
	bottom: 0;
	left: 0;
	background: #0ef3f3e1;
}
.footBar{
	display: flex;
	flex-flow: row nowrap;
	justify-content: space-around;
}
.footBar >div{
	width: 25%;
	height: 50px;
	line-height: 50px;
}
em{
	font-family: "Microsoft Yahei";
	font-style:normal;
}
</style>

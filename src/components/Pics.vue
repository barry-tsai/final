<template>
<div>
    <div class="blanks"></div>
    <el-carousel :interval="4000" type="card" height="550px" class="bo">
        <el-carousel-item v-for="item in list" :key="item">
            <img class="medium" :src="item.title">
        </el-carousel-item>
    </el-carousel>
	<div class="bu"></div>
</div>
</template>

<script>
export default {
	name: 'Contact',
	props: {
		msg: String
	},
	data(){
		return{
			list:[
				{title:require('../assets/p1.jpg')},
				{title:require('../assets/p2.png')},
				{title:require('../assets/p3.jpg')},
				{title:require('../assets/p4.png')}
			]
		}
	}
}
</script>


<style>
.bo {
    margin-left: 10%;
    margin-right: 10%;
}

.bu {
    height: 80px;
}

.el-carousel__item:nth-child(2n) {
    background-color: #99a9bf;
    width: 700px;
}

.el-carousel__item:nth-child(2n+1) {
    background-color: #d3dce6;
    width: 700px;
}
</style>
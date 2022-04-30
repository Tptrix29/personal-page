<template>
    <div id="award_block">
        <h3>荣誉证书</h3><hr>
        <div class="award">
            <span>校级奖学金, </span><span class="prize">一等奖</span>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="javascript:void(0)" @click="show">View Certification...</a><br>
            <div class="award-pic" v-show="false">
                <img src=""><br>
            </div>

            <span>校级数学竞赛, </span><span class="prize">二等奖</span>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="javascript:void(0)" >View Certification...</a><br>
            <div class="award-pic" v-show="false">
                <img src="../assets/awards/math.jpg"><br>
            </div>

            <span>全国大学生数学建模竞赛, </span><span class="prize">三等奖</span>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="javascript:void(0)" @click="show">View Certification...</a><br>
            <div class="award-pic" v-show="false">
                <img src=""><br>
            </div>

            <span>iGEM(国际基因工程机器大赛) 2021, </span><span class="prize">Best Software Award</span>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="javascript:void(0)" @click="show">View Certification...</a><br>
            <div class="award-pic" v-show="igem_vis">
                <img src="../assets/awards/iGEM2021.jpg"><br>
            </div>

            <span>MIT xPRO 机器学习课程结业证书</span>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="javascript:void(0)" @click="show">View Certification...</a><br>
            <div class="award-pic" v-show="false">
                <img src=""><br>
            </div>

            <span>C语言计算机二级证书</span>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="javascript:void(0)" @click="show">View Certification...</a><br>
            <div class="award-pic" v-show="igem_vis">
                <img src=""><br>
            </div>
        </div>
    </div>
</template>

<script>

export default ({
    name: "Skills",
    data(){
        return{
            igem_vis: false
        }
    },
    methods:{
        show(){
            this.igem_vis = !this.igem_vis
        }
    }
})
</script>

<style scoped>
.award{
    margin: 0% 2%;
    line-height: 2em;
}

.prize{
    font-weight: bold;
}
.award .award-pic{
    text-align: center;
    
}

.award img{
    height: 40%;
    width: 60%;
}
</style>
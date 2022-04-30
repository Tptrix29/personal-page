<template>
    <div id="nav">
        <div class="block" id="basic_info" @click="clickToScroll(1)">基本信息</div>
        <div class="block" id="education" @click="clickToScroll(2)">教育经历</div>
        <div class="block" id="skill" @click="clickToScroll(3)">个人技能</div>
        <div class="block" id="certification" @click="clickToScroll(4)">荣誉证书</div>
        <div class="block" id="project" @click="clickToScroll(5)">项目经历</div>
    </div>
</template>

<script>
export default ({
    name:"navigator",
    data(){
        return{
            index:{
                '1': "personal_info",
                '2': "edu_block", 
                '3': "skill_block",
                '4': "award_block",
                '5': "pj_block"
            }
        }
    },
    methods:{
        clickToScroll(i){
            window.scrollTo(0, document.getElementById(this.index[i]).offsetTop-document.getElementById("nav").scrollHeight)
        }
    }
})
</script>

<style scoped>
#nav{
    top: 0px;
    left: 0px;
    right: 0px;
    opacity: 90%;
    padding: 1% 0%;
    background-color: rgb(54, 50, 50);
    width: 100%;
    position: fixed;
    text-align: center;
    visibility: visible;
}

#nav .block{
    display: inline-block;
    width:10%;
    padding: 1%;
    margin: 0% 2.5%;
    text-align: center;

    color: white;
}

#nav .block:hover{
    color: rgb(170, 167, 167);
}

</style>

<template>
    <div id="personal_info">
        <h3>基本信息</h3><hr>
        <div id="wrapper">
            <div class="personal-image">
            <img src="../assets/pimg.jpg" alt="TIAN PEI">
            </div>
            <div class="text-box">
                <div class="item"><span class="title">姓名：</span><span class="content">田霈</span></div>
                <div class="item"><span class="title">性别：</span><span class="content">女</span></div><br>
                <div class="item"><span class="title">年龄：</span><span class="content">20</span></div>
                <div class="item"><span class="title">微信：</span><span class="content">187 7475 1539</span></div><br>
                <div class="item"><span class="title">QQ：</span><span class="content">2833701040</span></div>
                <div class="item"><span class="title">邮箱：</span><span class="content">tpzl0222@gmail.com</span></div><br>
                <div class="item"><span class="title">研究方向：</span><br><span class="content">数据分析、深度学习</span></div>
            </div>
        </div>
    </div>
    
</template>

<script>
export default ({
    name:"BasicInfo"

})
</script>

<style scoped>
#wrapper{
    display: flex;
    vertical-align: middle;
    
}

.personal-image{
    height: 100%;
    width: 15%;
    margin: 1% 10% 1% 2%;
}

.personal-image img{
    height: 100%;
    width: 100%;
}

.text-box{
    padding: 0%;
    height: 100%;
    width: 80%;
}

.item{
    line-height: 1.8em;
    display: inline-block;
    width: 40%;
    padding: 1% 0%;
}

.title{
    font-weight: bold;
}

.content{
    color: rgb(36, 49, 105);
}


</style>

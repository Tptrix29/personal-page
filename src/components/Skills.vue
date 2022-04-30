<template>
    <div id="skill_block">
        <h3>个人技能</h3><hr>
        <div class="skill">
            <span class="catelog">编程能力</span><br>
            <span>高级程序设计语言：</span><span>C++, Java, Python</span><br>
            <span>数据分析相关：</span><span>SQL, R</span><br>
            <span>操作系统相关：</span><span>Linux/shell</span><br>
            <span>WEB前端：</span><span>HTML5, CSS3, JavaScript, Vue</span><br>
        </div><br>
        <div class="skill">
            <span class="catelog">英语</span><br>
            <span>CET-6：</span><span>579</span><br>
            <span>TOEFL iBT：</span><span>100</span><br>
        </div>
    </div>
</template>

<script>

export default ({
    name: "Skills"
})
</script>

<style scoped>
.skill{
    line-height: 2em;
    margin: 0% 2%;
}
.catelog{
    font-size: 1.2em;
    font-weight: bold;
    color:rgb(26, 70, 107);
}
</style>
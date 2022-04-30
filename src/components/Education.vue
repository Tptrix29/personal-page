<template>
    <div id="edu_block">
        <h3>教育经历</h3><hr>
        <div class="exp">
            <span class="degree">同济大学 本科 生物信息学&nbsp;&nbsp;2019.9～2023.6</span><br>
            <span class="grade"><b>GPA:</b> 4.63/5.00, 专业前5%</span><br>
            <span>课程内容：</span>
            <li>C/C++高级语言程序设计</li>
            <li>统计学</li>
            <li>现代生物计算环境</li>
            <li>生物信息学</li>
            <li>机器学习理论与方法</li>
            <li>数据仓库与数据挖掘</li>
            <li>……</li>
        </div><br>
        <div class="exp">
            <span class="degree">同济大学 本科辅修 软件工程&nbsp;&nbsp;2021.9～2023.6</span><br>
            <span>课程内容：</span>
            <li>离散数学</li>
            <li>数据结构与算法</li>
            <li>……</li>
        </div>
    </div>
</template>

<script>

export default ({
    name: "Skills"
})
</script>

<style scoped>
.exp{
    margin: 0% 2%;
    line-height: 2em;
}

.degree{
    color: rgb(29, 69, 161);
    font-weight: bold;
    font-size: 1.2rem;
}
</style>
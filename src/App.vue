<template>
  <div id="resume">
    <Navigator></Navigator>
    <h1 id="title">个人简历</h1>
    <hr>
    <BasicInfo class="info"></BasicInfo>
    <Education class="info"></Education>
    <Skills class="info"></Skills>
    <Awards class="info"></Awards>
    <Project class="info"></Project>
    <End></End>
  </div>
  
</template>

<script>
import Navigator from './components/Navigator.vue'
import BasicInfo from './components/BasicInfo.vue'
import Education from './components/Education.vue'
import Skills from './components/Skills.vue'
import Awards from './components/Awards.vue'
import Project from './components/Project.vue'
import End from './components/End.vue'

export default {
  name: 'App',
  components: {
    BasicInfo, Education, Skills, Awards, Project, Navigator, End
  }
}
</script>

<style>

#resume{
  background-color: rgb(255, 255, 247);
  overflow: auto;
  position: absolute;
  left: 0px;
  right: 0px;
}

#title{
  text-shadow: 2px 2px 3px #a8a8a8;
  margin: 8% 0% 2% 11%;
  color: rgb(28, 50, 131);
  letter-spacing: 0.3em;
}

.info{
    margin: 2% 10%;
    padding: 1%;
    border: 2px dashed #E6E6FA;
    border-radius: 10px;
    box-shadow: 5px 5px 6px #bbbbbb;
}

.info h3{
  text-indent: 10px;
  color: rgb(37, 67, 110);
  letter-spacing: 0.1em;
}

.info:hover{
  box-shadow: 8px 8px 8px #a8a8a8;
}
</style>

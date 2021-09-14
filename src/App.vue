<template>
  <div class="container">
    <div class="content">
      <Header/>
        <hr>
      <Profile/>
        <hr>
      <MySkills/>
        <hr>
      <MyEducation/>
        <hr>
      <MyExperience/>
        <hr>
      <MyProjects/>
        <hr>
    </div>
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Profile from './components/Profile.vue'
import MySkills from './components/MySkills.vue'
import MyEducation from './components/MyEducation.vue'
import MyExperience from './components/MyExperience.vue'
import MyProjects from './components/MyProjects.vue'

export default {
  components : {
    Header,
    Profile, 
    MySkills,
    MyEducation,
    MyExperience,
    MyProjects
  }
}
</script>


<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Who i Am</template>

    I am a young lady passionate about technology and innovation. I am a Software Developer currently focusing on Front End Development and UX/UI design. 
    I love teamwork and ready to lead a team to achieve the set goals. Am equipped with analytical and problem solving skills, and good with numbers. 
    I am filled with curiosity and always open to listen and learn more.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Education</template>

    Kenya Certificate of Secondary Education<br>Mary Mount Girls Secondary 2014-2017<br><br>
Technical University of Mombasa<br> BSc Statistics & Computer Science  2018-2023
    >.

    <br />

    More Details are available in <code>MY CV</code>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Software Projects</template>

    Get official tools and libraries for my software project at:<br>
     1.<a href="https://github.com/Lindsey-Amelia/Team-Tulearn" target="_blank" rel="noopener">Tulearn Website</a>.<br>
     Tulearn website helps improve accesibility of learning materials and also helps connect the tutors and students.<br> 
   <br>2. During the Microsoft's Game of Learners hackathon, my team and i came 
    up with a healthcare model called
    <a href="https://github.com/Lindsey-Amelia/TEAM-EXQUISITE" target="_blank" rel="noopener">Exquisite HealthCare System</a>
    Our main aim was to try to improve the accesibility of healthcare in the region.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Skills</template>
    Windows OS
    Adobe
    JavaScript
      Nodejs
      Python
      HTML/CSS 
      Communication skills
      Team Work
      Teamleadership

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Social Media</template>
    LinkedIn Account 
    <a href="https://www.linkedin.com/in/lindsey-amelia-omoto-b56ba920b/" target="_blank" rel="noopener">Lindsey Amelia Omoto</a>.
     <br>Twitter Account
    <a href="https://twitter.com.com/AmelinLindsey" target="_blank" rel="noopener">AmelinLindsey</a>.
   <br> Github account
    <a href="https://github.com/Lindsey-Amelia" target="_blank" rel="noopener">Lindsey-Amelia</a>.
  </WelcomeItem>
</template>

<template>
  <div>
    <h1>Resume</h1>

    <div class="paragraph">
      I'm a Self-Taught Unity Game Developer with hands-on experience in crafting interactive 2D and 3D applications. Based in Karnataka, India, I bring a strong technical foundation and a creative mindset to every project I work on.
      <br />
      <br />After graduating with a Bachelor's degree in Mechanical Engineering in 2022, I discovered my true calling in game development and have since dedicated myself to learning and building games that are both engaging and immersive.
      <br />
      <br />I love teamwork, but I can also go in solo mode on the task requirements.
      <br />
      <br /> I am currently seeking opportunities to work so if you have any opportunity feel free to 
      <router-link to="/contact">contact me</router-link>.
      <br />

      <div style="margin-top:20px; margin-bottom:20px;">
        <a class="download-link" href="d/Resume(Gunaraj Poojary).pdf" target="_blank"><i class="fa fa-download fa-lg fa-fw"></i> Download as PDF</a>
        <div style="clear:both"></div>
      </div>
    </div>
    <div class="photo">
      <img src="img/resume-photo.jpg" alt="Photo of Gunaraj" />
    </div>

    <div style="clear:both"></div>

    <div class="full-content">
      <h2>Work experience</h2>

      <h3>Unity Intern - Realfy Oasis Pvt Ltd</h3>
      <h4>Sep 2024 – March 2025</h4>

      <div> Developed an AR fitness app in Unity.
        <ul>
          <li>Tackled the challenge of building a real-time fitness tracking app using Unity and MoveNet for fast, 
            accurate pose detection with AI-driven personalization.</li>
          <li>Integrated Figma designs into Unity, implemented core app mechanics (Screen transition, Individual
Screen functionality), developed AI-generated diet/exercise plans, optimized UI with DOTween
animations, and ensured seamless API communication using Asynchronous programming.</li>
          <li>Enhanced performance and user engagement by delivering a fluid, responsive UI, proposing and
            implementing improved design workflows, and fostering effective collaboration with crossfunctional teams.</li>
        </ul>
      </div>

      <h2>Skills</h2>

<div class="skill-container">
  <div class="skill-set">
    <h3>Game Development (PC, Mobile)</h3>
    <SkillRate name="Unity (2D/3D)"/>
    <SkillRate name="Responsive Design"/>
    <SkillRate name="Mobile Optimization"/>
    <SkillRate name="Gameplay mechanics"/>
    <SkillRate name="UI systems"/>
    <SkillRate name="DOTween"/>
    <SkillRate name="Unity Animation System"/>
    <SkillRate name="Blender Modelling (Beginner)"/>
  </div>

  <div class="skill-set">
    <h3>Programming & Architecture</h3>
    <SkillRate name="C#"/>
    <SkillRate name="C++ (Beginner)"/>
    <SkillRate name="OOP"/>
    <SkillRate name="Programming Patterns (MVC, Object Pool, Singleton, Service Locator, Strategy, Factory, Observer, State)"/>
    <SkillRate name="SOLID Principles"/>
  </div>

  <div class="skill-set">
    <h3>Tools & Collaboration</h3>
    <SkillRate name="Git / GitHub"/>
    <SkillRate name="Jira (Agile)"/>
    <SkillRate name="ClickUp"/>
    <SkillRate name="Miro"/>
    <SkillRate name="Slack"/>
  </div>

  <div class="skill-set">
    <h3>Soft Skills</h3>
    <SkillRate name="Continuous Learning"/>
    <SkillRate name="Adaptability"/>
    <SkillRate name="Problem Solving"/>
    <SkillRate name="Team Collaboration"/>
  </div>
</div>

<div style="clear:both"></div>

      <h2>Education</h2>

      <h3>St. Joseph Engineering College Mangalore</h3>
      <h4>B.E. in Mechanical Engineering</h4>
      <div>Aug 2018 – Sept 2022</div>
      <div>CGPA: 6.8/10</div>

      <h3>Govt PU College Navunda</h3>
      <h4>PUC – PCMB</h4>
      <div>Jun 2016 – Mar 2018</div>
      <div>Percentage: 81.6/100</div>

      <h2>Languages</h2>

      <h3>Kannada</h3>
      <div>I am a native speaker of Kannada, which is my mother tongue.</div>

      <h3>English</h3>
      <div>I have fluent proficiency in English, both written and spoken.</div>

      <h3>Hindi</h3>
      <div>Basic proficiency in Hindi and can comfortably understand and speak.</div>

      <h2>Besides...</h2>
      <div>
        <h3>I ❤️ Video Games</h3>
        <div>Some of my favorite games of all time include *Sekiro: Shadows Die Twice*, *Far Cry 3 & 4*, *Grand Theft Auto V*, *Valorant*, *Genshin Impact*, and *Bullet Echo* and so on.</div>

        <h3>I 🧡 Anime</h3>
        <div>I'm a big fan of anime and manga series such as *One Piece*, *Naruto*, *Solo Leveling*, *Dr. Stone*, *Sakamoto Days*, *Wind Breaker*, and many others.</div>

      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import SkillRate from "@/components/SkillRate.vue";

export default Vue.extend({
  name: "Resume",
  components: {
    SkillRate,
  },
});
</script>

<style scoped>
h2 {
  font-weight: 100;
  font-size: 2em;
  margin: 0px;
  padding: 0px;
  padding-top: 50px;
}
h3 {
  font-weight: 100;
  font-size: 1.6em;
  margin: 0px;
  padding: 0px;
  padding-top: 30px;
}
h4 {
  font-weight: 100;
  font-size: 1.3em;
  margin: 0px;
  padding: 0px;
  padding-top: 15px;
  font-style: italic;
}

.paragraph {
  max-width: 700px;
}

.download-link {
  float:left;
  margin-right: 50px;
}

.full-content div {
  max-width: 800px;
}

.skill-set h3 {
  padding-bottom: 10px;
}

.photo img {
  width: 300px;
  height: 300px;
  object-fit: cover;
  border-radius: 50%;
}

.tech-stack {
  font-style: italic;
}

.photo {
  margin-top: 50px;
  text-align: center;
}

.skill-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  gap: 20px;
  flex-wrap: wrap;
}

.skill-set {
  min-width: 220px; /* adjust as needed */
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 30px;
    padding-left: 80px;
  }

  .skill-set {
    float: left;
    padding-right: 60px; 
  }
}
</style>
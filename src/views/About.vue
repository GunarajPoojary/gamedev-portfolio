<template>
  <div style="margin-bottom: 80px;">
    <h1>Hello!</h1>

    <div class="paragraph">
      <div>
        I'm <strong>Gunaraj Poojary</strong>, a passionate Unity game developer with 6 months of work experience.<br>
        I specialize in designing and building clean, scalable, and optimized C# code using industry-standard best practices.
      </div>

      <div> My expertise includes: Object-Oriented Programming, Programming Patterns, SOLID Principles, game logic implementation, API integration, and more.</div>

      <div style="margin-top: 40px;">I am currently seeking opportunities to work on exciting projects that challenge my skills and allow me to grow as a developer.<br>
        If you're looking for a dedicated and enthusiastic game developer, feel free to <router-link to="/contact">contact me</router-link>.
        You can reach me at <strong>gunarajpoojary579@email.com</strong> or <router-link to="/contact">through here</router-link>.</div>
    </div>

    <div class="photo">
      <img src="img/avatar.png" alt="Avatar of Gunaraj" /> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  margin-top: 50px;
  text-align: center;
}

.photo img {
  width: 200px; /* Adjust this value as needed */
  height: auto;
  border-radius: 20px;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 10px;
    padding-left: 80px;
  }
}
</style>
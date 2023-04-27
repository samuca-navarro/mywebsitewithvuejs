<template>
    <!-- <div class="container">
        <div class="menu">
            <div class="coluna 1">
                <RouterLink to="/"> <h3>Home</h3> </RouterLink>
            </div>
            <div class="coluna 2">
                <RouterLink to="/about"> <h3>More</h3> </RouterLink>
            </div>
            <div class="coluna 3">
                <RouterLink to="/contact"> <h3>Contact</h3> </RouterLink> 
            </div>
        </div>
    </div>    -->

  <div class="main-container">
    
    <div class="container-one">
      <div class="profile">
        <img src="../assets/perfil.jpg" alt="">
        <h3>Samuel Esdras Navarro</h3>
        <p class="profession">Software Developer</p>
      </div>
      <br>
      <div class="social-links">
          <div class="link">
            <img src="../assets/github2.jpeg" alt="">
            <a href="https://github.com/samuca-navarro"><h2>GitHub</h2></a>
          </div>
          <br>
          <div class="link">
            <img src="../assets/ln.jpeg" alt="">
            <a href="https://br.linkedin.com/in/samuel-navarro-17a60b199"><h2>Linkedin</h2></a>
          </div>
      </div>
    </div>

    <div class="container-two">
      <div class="about-me">
       <h1>About me</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing 
        elit, sed do eiusmod tempor incididunt ut labore et 
        dolore magna aliqua. Ut enim ad minim veniam, quis 
        nostrud exercitation ullamco laboris nisi ut 
        aliquip ex ea commodo consequat. Duis aute 
        irure dolor in reprehenderit in voluptate velit 
        esse cillum dolore eu fugiat nulla pariatur. 
        Excepteur sint occaecat cupidatat non 
        proident, sunt in culpa qui officia deserunt 
        mollit anim id est laborum</p>
      </div>
      <div class="knowledge">
       <h1>Technologies Studied</h1>
       <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing 
        elit, sed do eiusmod tempor incididunt ut labore et 
        dolore magna aliqua. Ut enim ad minim veniam, quis 
        nostrud exercitation ullamco laboris nisi ut 
        aliquip ex ea commodo consequat. Duis aute 
        irure dolor in reprehenderit in voluptate velit 
        esse cillum dolore eu fugiat nulla pariatur. 
        Excepteur sint occaecat cupidatat non 
        proident, sunt in culpa qui officia deserunt 
        mollit anim id est laborum
       </p>  
       <!-- <h1>Technologies Studied</h1>
       <div class="row">
          <div class="coluna">
           <img src="../assets/py.jpg" alt="">
          </div>
          <div class="coluna">
           <img src="../assets/js.jpg" alt="">
          </div>
       </div> -->
      </div>
      <br>
      <div>
        <div class="button-container">
          <div class="projects-button">
            <a href=""><h2>My Projects</h2></a>
          </div>
          <div class="projects-button">
            <a href="../public/cv.pdf" download target="_blank"><h2>My Resume</h2></a>
          </div>
          <div class="projects-button">
            <RouterLink to="/contact"> <h2>Contact me</h2> </RouterLink>
          </div>
        </div>
      </div>
    </div>    
  
  </div>
</template>

<script>
export default{

}
</script>

<style scoped>

.profession{
  text-align: center;
}

.projects-button a{
  align-content: center;
  text-decoration: none;
  padding: none;
  color: black;
}

.projects-button {
  background-color: rgb(80, 115, 146);
  margin: 5px; 
  border-radius: 10%;
}

img{
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 40%;
}

.logo{
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 40%;
  border-radius: 30%;
}

.profile img{
  border-radius: 50%;
}

.link a{
  text-decoration: none;
  color:black;
  text-align: center;
}

/* .link img{
  height: 1rem;
} */

.main-container{
  display: flex;
  flex-direction: row;
  background-color:rgb(161, 159, 156);
  border-radius: 25px;
}

.container-one{
  background-color:rgb(80, 115, 146);
  padding: 3%;
  width: 30%;
  border-radius: 25px;
}

.container-two{
  background-color: rgb(161, 159, 156);
  margin: 2.5%;
  width: 70%;
}

.about-me{
  text-align: left;
}

img{
  align-content: center;
  border-radius: 6%;
}

h3{
  text-align: center
}

a{
  text-align: center;
}

.coluna{
  float: left;
  width: 50%;
}
.row::after {
  clear: both;
  display: table;
}

</style>


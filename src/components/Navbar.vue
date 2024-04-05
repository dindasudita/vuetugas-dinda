<template>
  <div class="Nsatu">
    <nav>
        <img src="../assets/logonama.png" class="logodi">
    
            <ul>
                <li><a href="#Main">HOME</a></li>
                <li><a href="#About">ABOUT</a></li>
                <li><a href="#Skill">SKILL</a></li>
                <li><a href="#Experience">EXPERIENCE</a></li>
                <li><a href="#Contact">CONTACT</a></li>
            </ul>
        
    </nav> 
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Rubik:wght@300;400;500;600;700;800&display=swap");

.Nsatu{
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background: #fcf6f0;
  z-index: 1000;
}

nav{
  display: flex;
  width: 100%;
  padding: 20px 0;
  align-items: center;
  justify-content: space-between;
  margin: 0;
}

nav ul li{
    display: inline-block;
    list-style: none;
    margin: 10px 20px;
}

nav ul li a{
    text-decoration: none;
    color: #815854;
    font-weight: bold;
}

nav ul li a:hover{
    color: #543c3a;
}

.logodi{
  max-width: 250px;
  max-height: 50px;
}
</style>

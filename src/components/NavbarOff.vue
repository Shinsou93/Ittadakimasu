<template>
  <nav class="navbaroff">
    <div class="langages">
    <a href="#" class="logo">
          <img src="../assets/Khmer/DrapeauKhmer2.jpg" alt="monlogo" width="80%" >
    </a>
    <a href="#" class="logo">
          <img src="../assets/LogoDivers/DrapeauFR.jpg" alt="monlogo" width="80%">
    </a>
    <a href="#" class="logo">
          <img src="../assets/Japan/DrapeauJP.jpg" alt="monlogo" width="80%">
    </a>
    </div>
      <ul class="navbaroff-menu">
        <li class="navbaroff-item">
          <a href="#" class="navbaroff-link">
            <i class="fas fa-home navbaroff-icon"></i>
            <span class="navbaroff-title">Accueil</span>
          </a>
        </li>
        <li class="navbaroff-item">
          <a href="Recettes" class="navbaroff-link">
            <i class="fas fa-folder navbaroff-icon"></i>
            <span class="navbaroff-title">Recettes</span>
          </a>
        </li>
        <li class="navbaroff-item">
          <a href="Forum" class="navbaroff-link">
            <i class="fas fa-home navbaroff-icon"></i>
            <span class="navbaroff-title">Forum</span>
          </a>
        </li>
        <li class="navbaroff-item">
          <a href="News" class="navbaroff-link">
            <i class="fa-solid fa-archway"></i>
            <span class="navbaroff-title">News</span>
          </a>
        </li>
        <li class="navbaroff-item">
          <a href="Connexion" class="navbaroff-link">
            <i class="fas fa-user navbaroff-icon"></i>
            <span class="navbaroff-title">Connexion</span>
          </a>
        </li>
      </ul>
  </nav>
</template>

<script>
export default {
  name: "navbarOff"
}
</script>

<style scoped>
body{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.navbaroff{
  position: fixed;
  width: 100%;
  padding: 0 2%;
  display: flex;
  justify-content: space-between;
  box-sizing: border-box;
  background-color: rgba(46, 49, 146, 0.8);
}

.langages{
  display: flex;
  justify-content: space-between;
  width: 10%;
  align-items: center;
}

.navbaroff ul{
  display: flex;
  justify-content: flex-end;
  justify-content: space-between;
  width: 50%;
  list-style-type: none;
  
}
.navbaroff li a{
  text-decoration: none;
  color: red;
  font-size: 16px;
  font-weight: bold;
}
</style>
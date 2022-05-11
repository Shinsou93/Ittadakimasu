<template>
    <div>
        <navbarOff />
            <img class="Headerimg" src="../assets/Khmer/fondAccueil.jpg" alt="bgaccueil">
            <h1 class="Titre">Bienvenu sur Ittadakimasu !</h1>
    </div>
</template>

<script>
import navbarOff from "../components/NavbarOff.vue"
export default {
  name: 'Accueil',
  components: {
      navbarOff
  }
}

</script>

<style scoped>
#Accueil {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.Headerimg{
    position: relative;
    width: 100%;
    height: 100vh;
    z-index: -1
;
}

.Titre {
    position: relative;
}
</style>
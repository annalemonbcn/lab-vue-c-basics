<template>
  <footer>
    <div class="info">
    <img src="../images/ironhack_logo.png" alt="ironhack logo">
    <p>2972 Westheimer Rd. Santa Ana,<br>Illinois 85486 </p>
  </div>
  <div class="links">
    <a href="#">Team</a>
    <a href="/Services/service.html">Services</a>
    <a href="#">About us</a>
    <a href="#">Press</a>
    <a href="/projects/project.html?uuid=1">Projects</a>
    <a href="#">Privacy Policy</a>
  </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterComp'
}
</script>

<style scoped>
footer{
  display: flex;
  flex-flow: row nowrap;
  justify-content: space-between;
  align-items: flex-start;

  margin-top: 5rem;
}
footer .info{
  display: flex;
  gap: 2rem;
}
footer .info img{
  max-width: 50px;
}

footer .links{
  display: grid;
  grid-template-columns: auto auto auto;
  grid-template-rows: auto auto ;
  justify-content: flex-start;
  gap: 1.5rem;
}
</style>
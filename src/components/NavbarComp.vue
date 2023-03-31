<template>
  <header>
    <a href="/" id="logo">
      <img src="../images/ironhack_logo.png" alt="ironhack logo" id="logo" />
    </a>
    <nav class="navbar" id="navbar">
      <ul class="navList">
        <li><a href="/">Link 1</a></li>
        <li><a href="/">Link 2</a></li>
        <li><a href="/">Link 3</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'NavbarCompo'
}
</script>

<style scoped>
header{
  display: flex;
  flex-flow: row nowrap;
  justify-content: space-between;
  align-items: center;
}

header #logo{
  max-width: 50px;
}

header .navbar ul{
  list-style-type: none;
  display: flex;
  gap: 1rem
}
</style>
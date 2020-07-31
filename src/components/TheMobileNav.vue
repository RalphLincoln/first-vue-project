<template>
  <section class="nav">
    <div class="nav-logo">
      <p style="font-size: 25px; color: white;">Ralph Lincoln</p>
    </div>
    <div class="nav-menu">
      <ul class="nav-menu-list">
        <li class="nav-list-item">About Me</li>
        <li class="nav-list-item">GitHub</li>
      </ul>
    </div>
  </section>
</template>


<script>
export default {};
</script>

<style lang="sass" scoped>
.nav
    background: #333
    display: flex
    flex-direction: column
    justify-content: space-around
    align-items: center
    .nav-logo
        margin: 20px auto
    .nav-menu
        width: 100%
.nav-menu-list
    list-style: none
    padding: 0
    .nav-list-item
        background: #222
        padding: 10px 20px
        text-align: center
        margin: 10px auto
        cursor: pointer
        width: 20%
        color: white
        &:hover
            width: 30% 
</style>
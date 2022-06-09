<template>
  <footer>
      <nav>
        <ul>
          <li>
            
          </li>
        </ul>
      </nav>

      <figure>
        <img src="../assets/img/dc-logo-bg.png" alt="">
      </figure>
  </footer>
</template>

<script>
export default {
  name: 'DcFooter',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

  footer{
    background-image: url("../assets/img/footer-bg.jpg");
    background-size: cover;
    height: 300px;
    display: flex;
    justify-content: space-between;
    

    figure{
      overflow: hidden;
      display: flex;
      align-items: center;
    }
  }

</style>
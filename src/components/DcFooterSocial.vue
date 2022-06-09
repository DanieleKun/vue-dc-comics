<template>
  <footer class="social-footer">
      <div class="button_container">
        <div class="my_button">
          <h3>Sign-Up Now!</h3>
        </div>
      </div>
      <div class="icon_social">
        <h3>Follow Us</h3>
        <img src="../assets/img/footer-facebook.png" alt="Social Facebook">
        <img src="../assets/img/footer-twitter.png" alt="Social Twitter">
        <img src="../assets/img/footer-youtube.png" alt="Social YouTube">
        <img src="../assets/img/footer-pinterest.png" alt="Social Pinterest">
        <img src="../assets/img/footer-periscope.png" alt="Social Periscope">
      </div>
  </footer>
</template>

<script>
export default {
  name: 'DcFooterSocial',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
$color_blue: rgb(2, 130, 249); 
    .social-footer{
        height: 70px;
        background-color: rgb(48, 48, 48);
        display: flex;
        justify-content: space-around;
        align-items: center;

        .my_button{
          display: inline-block;
          border: 2px solid $color_blue;
          padding: 5px;
          color: white;
        }

        .icon_social{
          color: $color_blue;
          display: flex;
          justify-content: space-around;
          align-items: center;

          img{
            margin: 0 20px;
          }
        }
    }
</style>
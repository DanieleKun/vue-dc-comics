<template>
  <header>
  <a href="">
    <img src="../assets/img/dc-logo.png" alt="Logo DC">
  </a>
  <nav>
    <ul>
      <li v-for="(link, i) in links" :key="i">
        <a :href="link.url" :class="link.current ? 'active' : ''">
        {{link.text}}
        </a>
      </li>
    </ul>
  </nav>

  </header>
</template>

<script>
export default {
  name: 'DcHeader',
  data(){
    return {
      links: [
        {
          text:"Characters",
          url: "#",
          current: "false"
        },
        {
          text:"Comics",
          url: "#",
          current: "true"
        },
        {
          text:"Movies",
          url: "#",
          current: "false"
        },
        {
          text:"Tv",
          url: "#",
          current: "false"
        },
        {
          text:"Games",
          url: "#",
          current: "false"
        },
        {
          text:"Collectibles",
          url: "#",
          current: "false"
        },
        {
          text:"Videos",
          url: "#",
          current: "false"
        },
        {
          text:"Fans",
          url: "#",
          current: "false"
        },
        {
          text:"News",
          url: "#",
          current: "false"
        },
        {
          text:"Shop",
          url: "#",
          current: "false"
        },
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header {
  display: flex;
  justify-content: space-around;
  align-items: center;

  img{
    width: 70px;
    margin: 10px;
  }
}
  ul {
    list-style-type: none;
    margin: 20px 0;

    li{
      display: inline-block;

      a {
        color: rgb(70, 70, 100);
        text-decoration: none;
        padding: 0 10px;

        &.active{
          color: rgb(2, 130, 249);
        }
      }
    }
  }
</style>
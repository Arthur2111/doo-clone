<template>
  <div class="navbar">
      <div class="logo">
        <a href="#"
          ><img
            src="https://www.dooprimeglobal.com/wp-content/themes/DP3-1104/style/images/common/logo-dp-dark.svg"
            alt="DooLogo"
        ></a>
      </div>
      <MegaHeader
      v-for="cont in content"
      :key="cont.id"
      :content="cont.content"
       ></MegaHeader>
  </div>
</template>


<script>
import MegaHeader from './MegaHeader.vue'

export default {
  components: {
    MegaHeader,
  },
  data() {
    return {
      contents: [
        {
          id: '1',
          content: 'market'
        }
      ]
    }
  }

};
</script>

<style scoped>
.navbar {
  background: white;
  padding: 1em;
}

.logo{
  display: flex;
}




</style>
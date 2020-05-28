<template>
  <Layout>
    <h1>About us</h1>
      <section id="app" class="section container">    

   <!-- create our grid -->
    <div class="columns is-multiline" v-if="gifs">
      <div class="column is-one-quarter" v-for="gif in gifs">

        <!-- the gif box -->
        <div class="gif-box">
       <!-- gif image and link -->
          <a :href="gif.url">
            <img class="gif-image" :src="gif.images.original.url">
          </a>

      <!-- gifs author -->
          <a 
            class="gif-user" 
            v-if="gif.user" 
            :href="gif.user.profile_url">
              <img :src="gif.user.avatar_url" height="40" width="40">
              {{ gif.user.display_name }}
          </a>
        </div>

      </div>
    </div>

  </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'About us'
  }
}
</script>
<style scoped>
<style>
    .gif-box {
        position: relative;
        background: #333;
    }
    .gif-user   {
        display: flex;
        align-items: center;
        position: absolute;
        left: 15px;
        bottom: 15px;
    }
    .gif-user img {
        margin-right: 8px;
    }
</style>

</style>
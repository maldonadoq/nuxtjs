<template>
  <h1>Welcome to my first Nuxt app</h1>
</template>

<script>
export default {
  head(){
    return {
      title: 'Application Nuxt Blocs | Home',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Website about post'
        }
      ],
      htmlAttrs:{
        lang: 'en'
      }
    }
  }
}
</script>
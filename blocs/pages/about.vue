<template>
  <div>
    <h1>About Us</h1>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Explicabo nisi quasi fugiat! Labore, debitis enim. Dolores, illum laudantium ut quam tenetur nesciunt exercitationem quis quibusdam voluptate earum veritatis praesentium vitae?</p>
  </div>
</template>

<script>
export default {
  head(){
    return  {
      title: 'Application Nuxt Blocs | About',
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
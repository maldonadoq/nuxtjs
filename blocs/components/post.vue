<template>
  <nuxt-link :to="'/posts/' + id">
    <div class="post">    
      <p>{{id}} - {{title}}</p>
    </div>
  </nuxt-link>
</template>

<script>
export default {
  name: 'post',
  props: ['id', 'title']
}
</script>

<style>
  .post{
    padding: 1rem;
    border: 1px solid whitesmoke;
    margin: 1rem 0;
  }

  .post:hover{
    border: 1px solid #6c5ce7;
    cursor: pointer;
  }

  a{

  }
</style>
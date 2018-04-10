<template>
  <div class="about">
      <h1>Hello {{ their_name }}, this is an about page</h1>
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Autem quae, delectus provident, error nulla reiciendis voluptatum incidunt neque consequuntur vel soluta quas totam molestias ut. Culpa voluptatem veniam dolor accusantium.</p>
  </div>
</template>

<script>
export default {
 name:'Skills',
 data(){
     return{
         their_name: this.$route.params.name
     }
 }
}
</script>


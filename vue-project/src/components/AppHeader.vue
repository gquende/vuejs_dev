<template>

  <h1>Olá Mister {{quende}}</h1>

  <HelloWorld msg="Em que posso ser útil?" />

</template>

<script>




import { defineComponent } from 'vue'
import HelloWorld from '@/components/HelloWorld.vue'

export default defineComponent({

  name:"AppHeader",
  components: { HelloWorld },

  //Cria os dados para serem mostrados no template
  data(){

    return {
      quende:"Geral"

    };
  }

});
</script>
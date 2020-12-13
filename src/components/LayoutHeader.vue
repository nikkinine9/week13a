<template>
 <header>
   <h3>{{ sitename }}</h3>
 </header>
</template>

<script>
export default {
  name: "LayoutHeader",
  props: {
    sitename: String,
  },
  mounted(){
  },
  beforeCreate(){
  },
  created(){
  },
  updated() {
  },

 
}
</script>

<style scoped>
header {
  background-color: navy;
  color:aliceblue;
  text-align: center;
  padding: 3rem 1rem;
}
</style>

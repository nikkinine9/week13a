<template>
  <nav>
      <ul>
          <li v-for="(link, index) in links" :key="index">
              <a :href="link.url">
              {{ link.label }}
              </a>
          </li>
      </ul>
  </nav>
</template>

<script>
export default {
    name: 'LayoutSidebar',
    props: {
        links: Array
    }
}
</script>

<style scoped>
nav {
    width: 200px;
    background-color: blue;
    
}

nav ul {
    list-style-type: none;
}

nav ul li {
    padding: 1rem;
    border-bottom: 1px solid aliceblue;
}

a {
    color: aliceblue;
}
</style>

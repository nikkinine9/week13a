<template>
  <main>
      <layout-sidebar :links="navigationLinks"></layout-sidebar>
      <article>
          <br>
        <p>Wonder what today will bring?</p>
      </article>
  </main>
</template>

<script>
import LayoutSidebar from './LayoutSidebar.vue'

export default {
    name: 'LayoutMain',
    components: {
        LayoutSidebar
    },
    data() {
        return{
            navigationLinks: [
                {label: 'Home', url: '/home.html'},
                {label: 'About', url: '/about.html'},
                {label: 'Location', url: '/Location.html'},
                {label: 'Contact', url: '/contact.html'}
            ]
        }
    }

}
</script>

<style scoped>
main {
    display: grid;
    grid-template-columns: 200px 1fr;

}

article {
    padding: 1rem;
}
</style>

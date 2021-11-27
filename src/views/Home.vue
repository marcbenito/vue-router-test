<template>
  <div class="home">
    
    
    <ul>
      <li>
        <reusable-content msg="texto 1" image="https://picsum.photos/640/360?1"></reusable-content>
      </li>
      <li>
        <reusable-content msg="texto 1" image="https://picsum.photos/640/360?2"></reusable-content>
      </li>
      <li>
        <reusable-content msg="texto 1" image="https://picsum.photos/640/360?3"></reusable-content>
      </li>
    </ul>
  </div>
</template>

<script>
// @ is an alias to rgba(168, 168, 39, 0.534))
import ReusableContent from '@/components/ReusableContent.vue'


export default {
  name: 'Home',
  components: {
    ReusableContent
  }
}
</script>

<style scoped>
.home {
   background-color:rgba(181, 209, 181, 0.562);
}

</style>
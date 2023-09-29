<script setup>

import { RouterView } from 'vue-router'

import BlogHeader from './views/BlogHeader.vue';
import JumboHead from './views/JumboHead.vue';
</script>


<template>

  <div class="container">
  <BlogHeader> </BlogHeader>
  <JumboHead text_title="ยินดีต้อนรับสู่BarberMiniMap" desc_box="รวมร้าน&สถานที่ไว้เที่ยวนั่งชิว จิบกาแฟหวานๆ"></JumboHead>
  <RouterView/>
  </div>

</template>

<script>
export default {
  name: 'App',
};
</script>
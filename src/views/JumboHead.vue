<template>
    <div class="p-4 p-md-5 mb-4 rounded text-body-emphasis bg-body-secondary">
        <div class="col-lg-9 px-0">
          <h1 class="display-3">{{ text_title }}</h1>
          <p class="lead my-3"> {{ desc_box }}</p>
        </div>
      </div>
  </template>
  
  <script setup>
  defineProps({
  text_title: {
    type: String,
    required: true
  },
  desc_box: {
    type: String,
    required: true
  }
  })
  </script>
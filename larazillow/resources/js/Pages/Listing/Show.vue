<template>
    <div>
      <ListingAddress :listing="listing" />
    </div>
  </template>
  
  <script setup>
  import ListingAddress from '@/Components/ListingAddress.vue'
  defineProps({
    listing: Object,
  })
  </script>

<script>
import MainLayout from '../../Layouts/MainLayout.vue';
export default {
  layout: MainLayout
}
</script>
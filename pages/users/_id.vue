<template>
  <div>
    <h1>Users Detail for {{ id }}</h1>
    <p>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Minima dolore
      hic, animi dicta expedita tenetur facere odit. Itaque, ipsa soluta?
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params

definePageMeta({
  layout: 'users',
})
</script>

<style scoped></style>

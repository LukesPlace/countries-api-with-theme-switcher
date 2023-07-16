<script setup lang="ts">

</script>

<template>
  <div class="bg">
    <div class="content-container">
      <div class="country-input">
        <i class="fas fa-search search-icon"></i>
        <input  placeholder="Search for a country...">
      </div>
      <select>
        <option>Africa</option>
        <option>America</option>
        <option>Asia</option>
      </select>
    </div>
  </div>
</template>

<style scoped>

.bg {
  background-color: hsl(207, 26%, 17%);
  color:white;
}

.content-container {
  margin: 1rem;
}

input, select {
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  border: none;
  outline: none;
  background: none;
  box-shadow: none;
  padding: 0;
  margin: 0;
}

.country-input {
  display: flex;
  width: 100%;
  background-color: hsl(209, 23%, 22%);
  height: 3rem;
  border-radius: 5px;
  align-items: center;
  opacity: 100%;
}

.country-select {
  display:flex;
  height: 3rem;
  width: 50%;
}
.search-icon {
  padding-left: 1rem;
  padding-right: 1rem;
}
</style>
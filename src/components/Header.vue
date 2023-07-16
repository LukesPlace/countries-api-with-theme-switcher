<script setup lang="ts">

function toggleDarkMode() {

}
</script>

<template>
  <div class="bg">
    <header>
      <div class="header-left">
        <h1>Where in the World?</h1>
      </div>
      <div class="header-right">
        <button @click="toggleDarkMode" class="dark-mode-button">
          <i class="fas fa-moon"></i>
          Dark Mode
        </button>
      </div>
    </header>
  </div>
</template>

<style>
.bg {
  background-color: hsl(209, 23%, 22%);

}
header {
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1.5rem;
  color: white;
}

.header-left h1 {
  background-color: hsl(209, 23%, 22%);
  font-size: 1.5rem;
  font-weight: bold;
}

.header-right .dark-mode-button {
  color:white;
  background-color: transparent;
  border: none;
  cursor: pointer;
  display: flex;
  align-items: center;
}

.header-right .dark-mode-button i {
  margin-right: 0.5rem;
}
</style>
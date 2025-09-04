<script setup>
import '@fortawesome/fontawesome-free/css/all.css'
</script>

<template>
  <div class="nav-tab">
    <ul>
      <li>
        <a href="#about">
          <i class="fas fa-circle-info icon"></i>
        </a>
      </li>
      <li>
        <a href="#project">
          <i class="fas fa-cubes icon"></i>
        </a>
      </li>
      <li>
        <a href="#reading">
          <i class="fas fa-book-open icon"></i>
        </a>
      </li>
      <li>
        <a href="#music">
          <i class="fas fa-music icon"></i>
        </a>
      </li>
      <li>
        <a href="#music">
          <i class="fas fa-gamepad icon"></i>
        </a>
      </li>
      <!-- Other nav items -->
    </ul>
  </div>
</template>

<style scoped>
.nav-tab{
    position: fixed;
    right: 0;
    top: calc(50vh - 125px);
    height: 250px;
    background: var(--bg-light);
}

.icon {
    padding: 5px;
    font-size: 35px;
    color: var(--text-muted);
}
.icon:hover {
    color: var(--text);
}
</style>

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
        <a href="#gaming">
          <i class="fas fa-gamepad icon"></i>
        </a>
      </li>
      <li>
        <a href="#picture">
          <i class="fas fa-images icon"></i>
        </a>
      </li>
    </ul>
  </div>
</template>

<style scoped>
.nav-tab{
    position: fixed;
    right: 0;
    top: 50vh;
    transform: translateY(-50%);
    height: var(--nav-bar-size);
    background: var(--bg-light);
    padding: var(--spacing2);
    border-radius: var(--radius-lg) 0 0 var(--radius-lg); /* top-left, top-right, bottom-right, bottom-left */
}
ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: var(--spacing2);
}
li {
    margin: 0;
    padding: 0;
}
a {
    text-decoration: none;
    display: flex;
    align-items: center;
    justify-content: center;
}
.icon {
    padding-top: var(--spacing2);
    padding-bottom: var(--spacing2);
    padding-left: var(--spacing1);
    font-size: var(--icon-size);
    color: var(--text-muted);
    display: block;
}
.icon:hover {
    color: var(--text);
}
</style>

<template>
  <div id="nav">
    <router-link class="logo" to="/">Events</router-link>
    <nav>
      <router-link :to="{ name: 'event-list' }">Event List</router-link> |
      <router-link :to="{ name: 'event-create' }">Create Event</router-link>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style  scoped>
#nav{
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding:1rem 2rem;
  background: #444;
  position: sticky;
  top: 0;
  right: 0;
  left: 0;
  bottom: 0;
}

.logo {
  font-size: 2rem;
}
nav {
  font-size: 1.2rem;
}

</style>

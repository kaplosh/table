<script setup lang="ts">
import HelloWorld from "./components/HelloWorld.vue";
import TheWelcome from "./components/TheWelcome.vue";
</script>

<template>
  <header>
      Testing table
  </header>

  <main>
    <table>
      <caption>Testing Table</caption>
      <thead>
        <tr >
          <th>ID</th>
          <th>Name</th>
          <th>Last name</th>
          <th>Class</th>
          <th>Date of Birth</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>69</td>
          <td>Pavel</td>
          <td>Marek</td>
          <td>1.A</td>
          <td>6.9.1969</td>
        </tr>

      </tbody>
    </table>
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
  table {
    border: 1px solid black;
  }
  td,
  th {
    border: 1px solid black
  }

}
</style>

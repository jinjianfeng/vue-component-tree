<template>
    <div>
        <h2>Vue component tree</h2>
        <a href="https://github.com/asvae/vue-component-tree">Repo</a>
        <ul>
            <li>Display your components as a tree or flat list.</li>
            <li>Preview components on the page.</li>
            <li>Text search (keybind: press Shift then Shift)</li>
            <li>Routing support.</li>
            <li>Saves on page reload.</li>
            <li>Colored statuses.</li>
        </ul>
    </div>
</template>

<script lang="ts">
  export default {
    $componentTree: {
      status: 'stable',
      description: `
      This file contains some info taken from repo. Long one.
      We can do multilines
      ## But not headers yet.
      `
    },
    data (){
      return {
        some: 'some',
      }
    },
  }
</script>

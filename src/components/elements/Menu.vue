<template>
  <div id="menu">
    <ul>
      <li>
        <a>Create a Todo item</a>
      </li>
      <li>
        <a>View our policies</a>
      </li>
    </ul>
  </div>
</template>

<script lang="ts">

import { Component, Vue } from 'vue-property-decorator';

@Component
export default class Menu extends Vue {
}

</script>

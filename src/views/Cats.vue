<template>
  <div>
    <b-table striped hover :items="items"></b-table>
  </div>
</template>

<script>
import cats from "@/data/cats";

export default {
  data() {
    return {
      cats
    };
  }
};
</script>
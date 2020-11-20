<template>
  <v-container>
    <v-row class="px-15">
      <calculator/>
    </v-row>
  </v-container>
</template>

<script>
import Calculator from "@/views/Calculator";
export default {
  name: "Home",
  components: {Calculator}
}
</script>

<style scoped>

</style>
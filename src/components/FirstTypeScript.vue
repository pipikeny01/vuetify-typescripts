<template>
  <div>
    <div>{{Test}}</div>
    <input type="text" v-model="this.Test" />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Component from "vue-class-component";

@Component({})
export default class FirstTypeScript extends Vue {
  public Test: string = "gogogo";
  constructor() {
    super();
  }

  mounted() {}
}
</script>

<style scoped>
</style>
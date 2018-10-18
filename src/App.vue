<template>
  <div>
    <form-helper>
      <h2 slot="title">{{title}}</h2>
      <p slot="text">I am a paragraph</p>
    </form-helper>
  </div>
</template>

<script>
import formHelper from "./components/formHelper.vue";

export default {
  components: {
    "form-helper": formHelper
  },
  data() {
    return {
      title: 'I am a dynamic title'
    };
  },
  methods: {}
};
</script>

<style>
</style>

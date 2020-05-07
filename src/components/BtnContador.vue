<template>
  <p>
    <button @click="contador++" class="btn btn-primary">
      {{nombre}}
      <span class="badge badge-danger">{{contador}}</span>
    </button>
  </p>
</template>

<script>
export default {
  props: ["nombre"],
  data() {
    return {
      contador: 0
    };
  }
};
</script>


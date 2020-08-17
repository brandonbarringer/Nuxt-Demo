<template>
  <h1>{{ message }}</h1>
</template>

<script>
  export default {
    name: 'HelloWorld',
    props: {
      message: {
        type: String,
        default: 'No String Input'
      }
    }
  };
</script>
<template>
  <p>{{ message }}</p>
</template>

<script>
  export default {
    data: () => {
      console.log('Vuejs is installed!');
      return {
        message: 'Hey, this is Vue!',
      };
    },
  };
</script>

<style>
p {
  color: green;
}
</style>

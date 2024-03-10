<template>
    <div>
      <h2>Text Input Page</h2>
      <textarea v-model="inputText" rows="4" cols="50"></textarea>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        inputText: '',
      };
    },
  };
  </script>
  
  <style scoped>
  h2 {
    font-size: 1.5em;
    margin-bottom: 20px;
  }
  textarea {
    resize: none;
  }
  </style>
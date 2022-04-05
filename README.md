```vue
<template>
  <h1>Hi!</h1>
</template>

<script>
  export default {
    layout: "clean",
    data() {
      return {
        roomNumber: "",
        password: ""
      };
    },
    methods: {
      getInfoAboutMe() {
        return {
          name: 'Dario',
          lastName: 'Tecchia',
          dob: '16 Sep 1994'
        }
      },
      getCurrentWorkplace() {
        return {
          workplace: {
            company: 'NTT Data Italia',
            position: 'Digital Engineer'
          }
        };
      },
      getSkills() {
        return [
          'web development',
          'problem solving',
          'php',
          'mysql',
          'javascript',
          'html5',
          'css3',
          'nodejs',
          'mongodb',
          'vuejs',
          'nuxtjs',
          'angular',
          'python',
          'express',
          'mongoose',
          'git',
          'github',
          'bitbucket',
          'gitlab',
          'java'
        ]
      }
    }
  };
</script>

<style lang="css" scoped>
  
</style>
```

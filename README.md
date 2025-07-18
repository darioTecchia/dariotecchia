```vue
<template>
  <h1>Hi!</h1>
</template>

<script>
  export default {
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
            company: 'Amaris',
            position: 'Consultant'
          }
        };
      }
    }
  };
</script>

<style lang="scss" scoped>
  
</style>
```

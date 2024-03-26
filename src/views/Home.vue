<template>
  <HomeWork>
      <template v-slot:default>
        <HomeWorkForm />
      </template>
  </HomeWork>
</template>

<script>
import HomeWork from '@/components/HomeWork'
import HomeWorkForm from '@/components/HomeWorkForm'

export default {
  name: 'Home',

  components: {
    HomeWork,
    HomeWorkForm
  }
}
</script>

<template>
<Layout>
    <Head title="Welcome" />
    <h1>Welcome to our app  {{ user.name }}</h1>
</Layout>
</template>

<script>
  import Layout from '@/Shared/Layout'
  import { Head } from '@inertiajs/inertia-vue3'

  export default {
    components: {
      Head,
      Layout,
    },
    props: {
      user: {name:'Kennedy'}
    },
  }
</script>

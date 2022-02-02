<template>
<Layout>
    <Head title="About" />
    <h1>About</h1>
</Layout>
</template>

<script>
  import Layout from '@/Shared/Layout'
  import { Head } from '@inertiajs/inertia-vue3'

  export default {
    components: {
      Head,
      Layout,
      name:About,
    },
    props: {
      user: {name:'Kennedy'}
    },
  }
</script>

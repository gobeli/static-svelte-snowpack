
<script>
import Layout from '../pages/_layout.svelte'

export let page
</script>

<Layout>
  <svelte:component this={page} />
</Layout>

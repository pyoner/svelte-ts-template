<h1>Hello {name}!</h1>
<p>
  <Counter />
  <Counter value={1}>Counter 1</Counter>
  <Counter value={100} step={3}>Counter 2</Counter>
</p>

<style>
  h1 {
    color: purple;
  }
</style>

<script lang="ts">
  import Counter from "./Counter.svelte";

  export let name: string;
</script>

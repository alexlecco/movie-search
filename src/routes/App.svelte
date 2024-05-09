<script>
  import Counter from './Counter.svelte'
  const initialCounter = 5
</script>

<Counter {initialCounter} />
<Counter />
<Counter initialCounter={2}/>
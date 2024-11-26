<h1>Test 2 Page</h1>
<p>This is the content of the Test 2 page.</p>

<script>
  import { onMount } from 'svelte';

  onMount(() => {
    console.log('Effect has been run');
  });
</script>

<style>
  .green-square {
    width: 100px;
    height: 100px;
    background-color: green;
    display: inline-block;
    margin: 10px;
  }
</style>

<div class="green-square"></div>
<div class="green-square"></div>
<div class="green-square"></div>

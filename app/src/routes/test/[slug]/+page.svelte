<script>
	/** @type {{ data: import('./$types').PageData }} */
	let { data } = $props();
</script>

<h1>{data.title}</h1>
<div>{@html data.content}</div>

<p class="text-3xl text-red-600 font-bold underline">12345</p>

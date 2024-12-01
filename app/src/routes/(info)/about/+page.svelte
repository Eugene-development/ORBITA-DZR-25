<script>
	let count = $state(0);

	const apiUrl = import.meta.env.VITE_API_URL;
	$inspect(apiUrl);
</script>

<svelte:head>
	<title>О нас</title>
	<meta name="description" content="This is where the description goes for SEO" />
</svelte:head>

<div
  class="inline-flex animate-shine max-w-[350px] w-full items-center justify-center rounded-xl text-sm border border-white/10 bg-[linear-gradient(110deg,#000103,45%,#1e2631,55%,#000103)] bg-[length:200%_100%] px-4 py-5 transition-colors"
>
  <div class="flex flex-col gap-2">
    <h3 class="text-xl font-semibold text-neutral-200">Luxe</h3>
    <p class="text-sm leading-[1.5] text-neutral-400">
      Explore the new website that simplifies the creation of sophisticated dark
      mode components.
    </p>
  </div>
</div>


<p>О нас</p>
<div class="relative overflow-hidden group bg-black">
	<span class="invisible">Text Glitch</span>
	<span
	  class="text-neutral-400 absolute top-0 left-0 group-hover:-translate-y-full transition-transform ease-in-out duration-500 hover:duration-300"
	>
	  Text Glitch
	</span>
	<span
	  class="text-neutral-400 absolute top-0 left-0 translate-y-full group-hover:translate-y-0 transition-transform ease-in-out duration-500 hover:duration-300"
	>
	  Text Glitch
	</span>
  </div>
  <div class="w-full max-w-[350px] ">
	<div
	  class="group relative grid overflow-hidden rounded-xl px-4 py-5 shadow-[0_1000px_0_0_hsl(0_0%_20%)_inset] transition-colors duration-200"
	>
	  <span>
		<span
		  class="spark mask-gradient animate-flip before:animate-kitrotate absolute inset-0 h-[100%] w-[100%] overflow-hidden rounded-xl [mask:linear-gradient(white,_transparent_50%)] before:absolute before:aspect-square before:w-[200%] before:rotate-[-90deg] before:bg-[conic-gradient(from_0deg,transparent_0_340deg,white_360deg)] before:content-[''] before:[inset:0_auto_auto_50%] before:[translate:-50%_-15%]"
		>
		</span>
	  </span>
	  <span
		class="backdrop absolute inset-px rounded-[11px] bg-neutral-950 transition-colors duration-200"
	  ></span>
	  <div class="space-y-2 z-10">
		<h3 class="text-xl font-semibold text-neutral-200">Luxe</h3>
		<p class="text-sm leading-[1.5] text-neutral-400">
		  Explore the new website that simplifies the creation of sophisticated
		  dark mode components.
		</p>
	  </div>
	</div>
  </div>
  
  

<button onclick={() => count++}>
	clicks: {count}
</button>
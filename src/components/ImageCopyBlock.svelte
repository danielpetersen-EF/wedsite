<script lang="ts">
	export let imageUrl: string;
	export let title: string;
	export let bodyText: string;
</script>

<div class="flex flex-col md:flex-row mb-2">
	<div class="lg:w-1/5 md:w-1/2 max-w-sm">
		<img src={imageUrl} alt={title} class="w-full rounded" />
	</div>
	<div class="md:w-1/2 p-4">
		<h2 class="text-2xl text-primary-600 mb-4">{title}</h2>
		<p class="text-secondary-900">{bodyText}</p>
	</div>
</div>

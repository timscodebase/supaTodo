<script lang="ts">
	const { text } = $props() as { text: string };
</script>

<div class="rounded-md bg-red-100 p-4 my-3">
	<div class="text-sm leading-5 text-red-700">{text}</div>
</div>

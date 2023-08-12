<script lang="ts">
  export let title = "";
  export let date = "";
  export let description = "";
</script>

<div
  class="flex flex-col justify-center align-middle items-center rounded-full border-2 border-primary bg-primary w-48 h-48 p-3 text-center mx-2 mb-2 mt-2 text-white"
>
  <span class="mb-1">{title}</span>
  <span class="text-xs italic">{description} | {date}</span>
</div>

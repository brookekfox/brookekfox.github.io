<script lang="ts">
  export let school = "";
  export let location = "";
  export let graduationDate = "";
  export let degree = "";
  export let description = "";

  const screenSize = "md";
</script>

<div
  class="flex flex-col w-full mx-4 mb-4 mt-4 text-secondary border-b-2 border-dotted"
>
  <div
    class="flex flex-col {screenSize}:flex-row justify-between align-middle items-center mb-2 w-full p-2"
  >
    <span class="font-bold">{school}</span>
    <span class="italic">{location}</span>
    <span>{graduationDate}</span>
  </div>
  <div
    class="flex flex-row justify-between align-middle items-center mb-2 w-full p-2"
  >
    <span class="text-sm text-accent">{degree}</span>
    <span class="text-sm text-accent italic">{description}</span>
  </div>
</div>

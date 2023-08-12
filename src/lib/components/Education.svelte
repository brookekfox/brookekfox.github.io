<script lang="ts">
  export let school = "";
  export let location = "";
  export let graduationDate = "";
  export let degree = "";
  export let description = "";
</script>

<div
  class="flex flex-col w-full mx-4 mb-4 mt-4 border-2 border-primary bg-primary text-accent-2"
>
  <div
    class="flex flex-row justify-between align-middle items-center mb-2 w-full p-2"
  >
    <span class="font-bold">{school}</span>
    <span class="">{location}</span>
    <span class="">{graduationDate}</span>
  </div>
  <div
    class="flex flex-row justify-between align-middle items-center mb-2 w-full p-2"
  >
    <span class="text-sm">{degree}</span>
    <span class="text-sm italic">{description}</span>
  </div>
</div>

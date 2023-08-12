<script lang="ts">
  export let company = "";
  export let location = "";
  export let startDate = "";
  export let endDate = "present";
  export let position = "software engineer";
  export let description = "";
  export let descriptionSecondary = "";
</script>

<div class="flex flex-row w-full mx-4 mb-4 mt-4">
  <div
    class="flex flex-col justify-center align-middle items-center w-1/4 text-primary bg-accent-2 p-4 border-2 border-secondary text-xl font-bold"
  >
    {company}
  </div>
  <div class="border-2 border-secondary w-3/4 text-primary text-xs">
    <div class="flex flex-row justify-between align-middle items-center p-4">
      <!-- <h2 class="font-bold text-sm">{company}</h2> -->
      <h2 class="">{location}</h2>
      <h2 class="">{startDate} - {endDate}</h2>
    </div>

    <div
      class="flex flex-row justify-center align-middle items-center text-accent-2 bg-primary italic text-center p-3"
      style="font-size:x-small"
    >
      {position}
    </div>

    <div
      class="flex flex-col justify-between align-top items-start text-justify p-4"
    >
      <div>{description}</div>
      <div class="mt-2 italic">{descriptionSecondary}</div>
    </div>
  </div>
</div>

<style>
</style>

<script lang="ts">
  export let company = "";
  export let location = "";
  export let startDate = "";
  export let endDate = "present";
  export let position = "software engineer";
  export let description = "";
  export let descriptionSecondary = "";
  export let technologies = "";
</script>

<div class="flex flex-col md:flex-row !w-full mx-4 mb-4 mt-4">
  <div
    class="md:w-56 md:min-w-56 md:max-w-56 flex flex-row justify-center align-middle items-center text-primary bg-accent-2 p-4 border-2 border-secondary text-xl font-bold"
  >
    {company}
  </div>

  <div class="border-2 border-secondary text-primary text-xs w-full">
    <div class="flex flex-row justify-between align-middle items-center p-4">
      <h2>{location}</h2>
      <h2>{startDate} - {endDate}</h2>
    </div>

    <div
      class="flex flex-row justify-center align-middle items-center text-accent-2 bg-primary italic text-center p-4"
      style="font-size:x-small"
    >
      {position}
    </div>

    {#if description !== "" || descriptionSecondary !== ""}
      <div
        class="flex flex-col justify-between align-top items-start text-justify p-4"
      >
        <div>{description}</div>
        <div class="mt-2 italic">{descriptionSecondary}</div>
      </div>
    {/if}

    {#if technologies !== ""}
      <div
        class="flex flex-col justify-between align-top items-start text-justify p-4 bg-accent text-primary"
      >
        <div class="italic">Technologies: {technologies}</div>
      </div>
    {/if}
  </div>
</div>

<style>
</style>

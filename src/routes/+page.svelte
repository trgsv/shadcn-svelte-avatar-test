<script lang="ts">
  import * as Avatar from "$lib/components/ui/avatar";
</script>

<div class="grid w-full justify-center gap-12 mt-12">
    <Avatar.Root class='w-32 h-32'>
      <Avatar.Image src="https://picsum.photos/200" alt="random-pic" crossorigin="anonymous" />
      <Avatar.Fallback>Not loaded</Avatar.Fallback>
    </Avatar.Root>

    <img 
        class="w-32 h-32 rounded-full"
        src="https://picsum.photos/200"
        alt="random-pic"
        crossorigin="anonymous"
    />

    <Avatar.Root class='w-32 h-32'>
      <Avatar.Image src="https://github.com/huntabyte.png" alt="@huntabyte" crossorigin="anonymous" />
      <Avatar.Fallback>Not loaded</Avatar.Fallback>
    </Avatar.Root>

    <img
        class="w-32 h-32 rounded-full"
        src="https://github.com/huntabyte.png"
        alt="@huntabyte"
        crossorigin="anonymous"
    />
</div>

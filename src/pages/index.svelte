<script>
  import lirik from "../data/lirik";
</script>

<div class="p-2">
  <a
    href="https://play.google.com/store/apps/details?id=com.sholawat.jawa"
    class="p-2 px-3 rounded bg-violet-500 inline-block text-white"
    >kasih bintang 5</a
  >
  <div class="rounded overflow-hidden border mt-2">
    {#each lirik.sort() as x}
      <a
        class="block border-b p-2"
        href="#/lirik/{x.replaceAll(' ', '-').toLowerCase()}">{x}</a
      >
    {/each}
  </div>
</div>

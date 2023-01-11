<script>
  import lirik from "../data/lirik";
</script>

<div class="p-2">
  <div class="rounded overflow-hidden border mt-2">
    {#each lirik.sort() as x}
      <a
        class="block border-b p-2"
        href="#/lirik/{x.replaceAll(' ', '-').toLowerCase()}">{x}</a
      >
    {/each}
  </div>
  <div class="rounded text-sm overflow-hidden mt-3 border">
    <div class="bg-black text-white p-3 border-b">Support Me</div>
    <div class="p-3">
      Gopay : 0815 4514 3654 <br />
      Paypal : muhzaini30@gmail.com
    </div>
  </div>
</div>

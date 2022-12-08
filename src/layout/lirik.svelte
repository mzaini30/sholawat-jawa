<div class="p-3">
  <h1 class="text-center font-bold mb-3"><slot name="judul" /></h1>
  <div class="isi"><slot name="isi" /></div>
</div>

<style>
  .isi :global(pre) {
    @apply whitespace-pre-line font-sans;
  }
</style>

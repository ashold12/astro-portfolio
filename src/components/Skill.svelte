<script>
  export let image;
  export let title;
</script>

<div
  class="mb-4 font-bold text-sm text-gray-darker flex w-134 xsm:w-4/12 xmd:w-134 min-w-134 xl:w-4/12"
>
  <div class="w-40 h-40 object-contain inline-block mr-2">
    <img src={image} />
  </div>
  <span class="self-center">{title}</span>
</div>

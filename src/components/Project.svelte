<script>
  export let title;
  export let link;
  export let img;
  export let text;
</script>

<div class="flex flex-wrap sm:flex-nowrap mb-8">
  <div class="sm:mr-4 sm:ml-0 sm:w-5/12">
    <a href={link} target="_blank">
      <img
        src={img}
        class="rounded shadow-lg hover:filter-dark transition ease-in-out duration-250"
      />
    </a>
  </div>
  <div class="sm:w-7/12 mt-0">
    <a href={link} target="_blank">
      <h3
        class="sm:mt-0 sm:leading-none font-extrabold mb-2 text-gray-dark hover:underline hover: cursor-pointer"
      >
        {title}
      </h3>
    </a>
    <!-- Werewolf - Browser Party Game -->
    <p class="">
      {text}
    </p>
  </div>
</div>

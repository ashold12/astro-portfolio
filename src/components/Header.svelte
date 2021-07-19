<script>
  import face from "../images/edited.png";
</script>

<header
  class="bg-white p-6 block flex-col md:flex md:flex-row w-full md:justify-between md:items-start shadow-lg"
>
  <div name="user" class="md:flex">
    <img src={face} class="rounded-full w-32 ml-auto mr-auto md:ml-0 md:mr-0" />
    <div class="flex-col ml-auto mr-auto md:ml-8 md:mr-0">
      <h1
        class="text-center md:text-left text-4xl sm:text-4xl font-extrabold text-black"
      >
        Alexander Shold
      </h1>
      <h1 class="text-center text-gray-darker md:text-left text-2xl">
        Full Stack Software Engineer
      </h1>
    </div>
  </div>
  <div class="mt-2 md:mt-0 md:self-center text-center">
    <a
      class="btn text-2xl font-bold text-white bg-blue rounded px-6 py-4 md:self-center inline-block transition ease-in-out duration-500 hover:bg-blue-dark"
      href="mailto:ashold.12@gmail.com"
      target="_blank"
    >
      <i class="fas fa-paper-plane pr-2" />
      Contact Me
    </a>
  </div>
</header>

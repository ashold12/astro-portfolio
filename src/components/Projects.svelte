<script>
  import Project from "./Project.svelte";

  import werewolf from "../images/werewolf.jpg";
  import endorse from "../images/endorse.png";
  import catwalk from "../images/catwalk.png";
  import rest from "../images/backend.jpg";
</script>

<div name="projects" class="bg-white rounded p-4 shadow-lg">
  <h2>Projects</h2>
  <p class="mb-4">
    I'm not going to list this site here since you're already here. This page
    was made using no javascript/javascript frameworks. It is purely HTML and
    CSS composed via Tailwind.
  </p>
  <hr class="mt-7 mb-8 text-gray-darker" />
  <Project
    title="Werewolf - Browser Party Game"
    link="https://github.com/ashold12/werewolf"
    img={werewolf}
    text="Developed with a small team of engineers over five days and deployed on AWS. Heavily utlized sockets and event driven architecture to handle the game state. The game features a lobby, real time chat, conditional renders/permissions depending on player role."
  />
  <Project
    title="EndorseMe - CLI LinkedIn Automation Tool"
    link="https://github.com/ashold12/endorseMe/tree/master"
    img={endorse}
    text="Developed with a small team of engineers over five days and deployed on AWS. Heavily utlized sockets and event driven architecture to handle the game state. The game features a lobby, real time chat, conditional renders/permissions depending on player role."
  />
  <Project
    title="Catwalk - React Retail Web-Portal"
    link="https://github.com/ashold12/FEC-Catwalk"
    img={catwalk}
    text="Modular reviews component developed for retail web-portal. Utilized pre-existing legacy api to consume data as well as leave comments/reviews/product photos. Featured a modal for submitting new reviews with animated star rating component, sophisticated error handling and review sorting, and react portals for image uploads and report submissions."
  />
  <Project
    title="REST In Peace - Scaled Backend API/Microservice"
    link="https://github.com/ashold12/SDC"
    img={rest}
    text="Refactored legacy RESTFUL API with mirrored endpoints/request parameters to increase throughput. Imported and nested 15 million records of user data via Mongo shell, and used aggregation pipeline to nest data into highly consumable format.  Deployed on 8 AWS instances with Nginx load balancer."
  />
</div>

<script>
  import Skill from "./Skill.svelte";
</script>

<div class="bg-white rounded p-6 pl-4 w-full shadow-lg text-lg mb-4">
  <h2>Skills</h2>
  <p class="mb-4 text-base">
    I possess high expertise in modern Javascript, with experience across the
    complete stack and development cycle.
  </p>
  <h3 class="text-gray-darker mb-1 mt-2 text-lg">Front End</h3>
  <hr class="mb-2 text-gray-darker" />
  <div class="flex flex-wrap justify-between">
    <!-- SKILLS r1 -->
    <Skill title="Javascript" image="./images/logos/javascript.png" />
    <Skill title="ReactJS" image="./images/logos/react.png" />
    <Skill title="HTML5" image="./images/logos/html5.png" />
    <Skill title="CSS3" image="./images/logos/css3.png" />
    <Skill title="Tailwind" image="./images/logos/tailwind.svg" />
    <Skill title="jQuery" image="./images/logos/jquery.png" />
    <!-- Backend -->
    <h3 class="text-gray-darker mb-1 mt-2 w-full text-lg">Back End</h3>
    <hr class="mb-2 text-gray-darker w-full" />
    <Skill title="Node.js" image="./images/logos/node.png" />
    <Skill title="Express" image="./images/logos/express.png" />
    <Skill title="MongoDB" image="./images/logos/mongo.png" />
    <Skill title="MySql" image="./images/logos/mysql.png" />
    <Skill title="AWS" image="./images/logos/aws.png" />
    <Skill title="Socket.io" image="./images/logos/socket.png" />
  </div>
</div>

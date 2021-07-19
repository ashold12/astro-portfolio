<script>
  import Skill from "./Skill.svelte";

  import javascript from "../images/logos/javascript.png";
  import ReactJS from "../images/logos/react.png";
  import HTML5 from "../images/logos/html5.png";
  import CSS3 from "../images/logos/css3.png";
  import Tailwind from "../images/logos/tailwind.svg";
  import jquery from "../images/logos/jquery.png";
  import node from "../images/logos/node.png";
  import Express from "../images/logos/express.png";
  import mongo from "../images/logos/mongo.png";
  import MySql from "../images/logos/mysql.png";
  import AWS from "../images/logos/aws.png";
  import socket from "../images/logos/socket.png";
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
    <Skill title="Javascript" image={javascript} />
    <Skill title="ReactJS" image={ReactJS} />
    <Skill title="HTML5" image={HTML5} />
    <Skill title="CSS3" image={CSS3} />
    <Skill title="Tailwind" image={Tailwind} />
    <Skill title="jQuery" image={jquery} />
    <!-- Backend -->
    <h3 class="text-gray-darker mb-1 mt-2 w-full text-lg">Back End</h3>
    <hr class="mb-2 text-gray-darker w-full" />
    <Skill title="Node.js" image={node} />
    <Skill title="Express" image={Express} />
    <Skill title="MongoDB" image={mongo} />
    <Skill title="MySql" image={MySql} />
    <Skill title="AWS" image={AWS} />
    <Skill title="Socket.io" image={socket} />
  </div>
</div>

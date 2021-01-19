<script>
   import { showModal } from "../store";

   function copyEmail() {
      navigator.clipboard.writeText("apriliandi642@gmail.com");
      $showModal = true;
   }
</script>

<div class="container">
   <section class="about">
      <h1 class="title">About Me</h1>
      <div class="line" />

      <h3 class="about__intro">Hi, I am</h3>
      <h1 class="about__name">Farhan Apriliandi</h1>
      <p class="about__desc-1">
         I'm self taught programmer focus on Front-End.
      </p>
      <p class="about__desc-2">
         Currently, i am working for my personal projects and that project focus
         on front-end (web application or some tools).
      </p>
   </section>

   <section class="skills">
      <h1 class="title">My Skills</h1>
      <div class="line" />

      <p class="skills__desc">
         I primarily use the following technologies, tools, framework :
      </p>

      <ul>
         <li>Html</li>
         <li>Css</li>
         <li>Javascript</li>
         <li>Typescript</li>
         <li>Svelte</li>
         <li>Vue</li>
      </ul>
   </section>

   <section class="projects">
      <h1 class="title">My Projects</h1>
      <div class="line" />

      <div class="project">
         <a
            href="https://github.com/apriliandi246/my-STYLE"
            target="_blank"
            class="project__title"
            rel="noopener">my-STYLE</a
         >

         <p class="project__desc">
            Css style and components for my web application.
         </p>

         <span class="project__tech">Html</span>
         <span class="project__tech">Css</span>
         <span class="project__tech">Javascript</span>
      </div>

      <div class="project">
         <a
            href="https://github.com/apriliandi246/svelte-social-media"
            target="_blank"
            class="project__title"
            rel="noopener">svelte-social-media</a
         >

         <p class="project__desc">
            Make clone social media using Svelte, Sapper and Firebase.
         </p>

         <span class="project__tech">Svelte</span>
         <span class="project__tech">Sapper</span>
         <span class="project__tech">Firebase</span>
      </div>

      <div class="project">
         <a
            href="https://github.com/apriliandi246/quran"
            target="_blank"
            class="project__title"
            rel="noopener">read-quran</a
         >

         <p class="project__desc">
            Web application that allow you read Quran, read the interpretation
            and you can listen too.
         </p>

         <span class="project__tech">Vue</span>
      </div>

      <div class="project">
         <a
            href="https://github.com/apriliandi246/vscode-css-sort"
            target="_blank"
            class="project__title"
            rel="noopener">vscode-css-sort</a
         >

         <p class="project__desc">
            Visual Studio Code extension for make your css properties sorted,
            and make it easy to read.
         </p>

         <span class="project__tech">vscode-extension</span>
         <span class="project__tech">Typescript</span>
      </div>

      <a
         href="https://github.com/apriliandi246"
         target="_blank"
         rel="noopener"
         class="project__more">
         <img src="/github.png" alt="github" />
         <p class="more-project">More projects</p>
      </a>
   </section>

   <section class="contact">
      <h1 class="title">Get in Touch</h1>
      <div class="line" />

      <p class="contact__desc">
         I am often active on Twitter, but you can also contact me via Email.
      </p>

      <ul>
         <li>
            <a
               href="https://github.com/apriliandi246"
               target="_blank"
               rel="noopener">Github</a
            >
         </li>
         <li>
            <a
               href="https://gitlab.com/apriliandi246"
               target="_blank"
               rel="noopener">Gitlab</a
            >
         </li>
         <li>
            <a
               href="https://twitter.com/calon_jenazah__"
               target="_blank"
               rel="noopener">Twitter</a
            >
         </li>
         <li>
            <a
               href="https://www.linkedin.com/in/farhan-apriliandi-934442191/"
               target="_blank"
               rel="noopener">Linkedin</a
            >
         </li>
         <li on:click={copyEmail} class="email">apriliandi642@gmail.com</li>
      </ul>
   </section>

   <footer>
      <div class="line-2" />
      <p>💚 👨‍💻</p>
      <div class="line-2" />
   </footer>
</div>

<style>
   p {
      color: #ffffff;
      font-size: 1.1rem;
      line-height: 28px;
      font-family: monospace;
   }

   span {
      letter-spacing: 1px;
   }

   ul {
      display: flex;
      flex-direction: column;
   }

   ul li {
      padding: 13px;
      color: #ffffff;
      margin-top: 21px;
      font-size: 1.1rem;
      border-radius: 100px;
      letter-spacing: 1.3px;
      display: inline-block;
      font-family: monospace;
      border: 3px solid #8892b0;
      background-color: #2e1f3b;
   }

   ul li a {
      color: #ffffff;
      text-decoration: none;
   }

   ul li a:hover {
      color: #7488a5;
      text-decoration: underline;
   }

   ul li::before {
      width: 1.4em;
      color: #ffffff;
      content: "\25C7";
      margin-left: 2px;
      font-weight: bold;
      display: inline-block;
   }

   footer {
      display: flex;
      align-items: center;
      justify-content: center;
   }

   footer p {
      font-size: 1.9rem;
      margin-inline: 20px;
   }

   li.email {
      cursor: pointer;
      transition: transform 0.2s;
   }

   li.email:hover {
      transform: scale(1.02);
   }

   .container {
      width: 100%;
   }

   .line {
      height: 3px;
      width: 250px;
      border-radius: 10px;
      background-color: #8892b0;
   }

   .line-2 {
      width: 50px;
      height: 4px;
      border-radius: 20px;
      background-color: #8892b0;
   }

   .about__intro {
      color: #ccd8e2;
      margin-top: 30px;
      font-size: 1.7rem;
      font-family: monospace;
   }

   .about__name {
      color: #7488a5;
      font-size: 2.8rem;
      margin-top: 14px;
      line-height: 47px;
      font-weight: bold;
      font-family: monospace;
      text-shadow: 1px 1px #ffffff;
   }

   .title {
      color: #ffffff;
      margin-top: 14px;
      font-size: 1.6rem;
      font-weight: bold;
      line-height: 44px;
      margin-bottom: 5px;
      letter-spacing: 1.2px;
      font-family: monospace;
   }

   .about__desc-1 {
      margin-top: 20px;
   }

   .about__desc-2 {
      margin-top: 10px;
   }

   .skills__desc {
      margin-top: 28px;
      margin-bottom: 10px;
   }

   .project {
      padding: 20px;
      margin-top: 30px;
      border-radius: 20px;
      border: 3px solid #8892b0;
      background-color: #2e1f3b;
   }

   .project__title {
      color: #ccd8e2;
      font-size: 1.3rem;
      font-weight: bold;
      text-decoration: none;
      font-family: monospace;
   }

   .project__title:hover {
      color: #7488a5;
      text-decoration: underline;
   }

   .project__desc {
      margin-top: 20px;
   }

   .project__tech {
      padding: 12px;
      color: #ccd8e2;
      margin-top: 20px;
      font-size: 1.1rem;
      font-weight: bold;
      margin-right: 10px;
      border-radius: 20px;
      display: inline-block;
      font-family: monospace;
      background-color: #0a192f;
   }

   .project__more {
      display: flex;
      padding: 13px;
      cursor: pointer;
      margin-top: 40px;
      align-items: center;
      border-radius: 100px;
      text-decoration: none;
      justify-content: center;
      background-color: #2e1f3b;
      border: 3px solid #8892b0;
      transition: transform 0.2s;
   }

   .project__more:hover {
      transform: scale(1.03);
   }

   .project__more img {
      margin-right: 15px;
   }

   .project__more p {
      color: #ccd8e2;
      font-size: 1.1rem;
      font-weight: bold;
      letter-spacing: 1px;
   }

   .contact__desc {
      margin-top: 28px;
      margin-bottom: 10px;
   }

   footer {
      margin-bottom: 60px;
   }

   footer,
   .contact,
   .projects,
   .skills {
      margin-top: 160px;
   }

   @media screen and (min-width: 770px) {
      p {
         line-height: 26px;
      }

      .project a,
      a .more-project {
         font-size: 1.4rem;
      }

      p,
      ul li {
         font-size: 1.3rem;
      }

      .about__desc-2 {
         line-height: 30px;
      }
   }
</style>

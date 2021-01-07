<script>
</script>

<style>
   p {
      color: #ccd8e2;
      font-size: 1.2rem;
      line-height: 24px;
      font-family: monospace;
   }

   ul {
      display: flex;
      flex-direction: column;
   }

   ul li {
      padding: 11px;
      color: #ccd8e2;
      margin-top: 17px;
      font-size: 1.3rem;
      font-weight: bold;
      margin-right: 20px;
      border-radius: 4px;
      display: inline-block;
      font-family: monospace;
      background-color: #0a192f;
   }

   li a {
      color: #ccd8e2;
      text-decoration: none;
   }

   li a:hover {
      color: #7488a5;
      text-decoration: underline;
   }

   ul li::before {
      width: 1.4em;
      color: #8dafce;
      content: "\00BB";
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
      font-size: 2rem;
      margin-inline: 25px;
   }

   .container {
      width: 100%;
   }

   .line {
      height: 2px;
      width: 250px;
      border-radius: 32%;
      background-color: #8892b0;
   }

   .line-2 {
      height: 3px;
      width: 120px;
      border-radius: 50%;
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
      font-size: 3rem;
      margin-top: 14px;
      font-weight: bold;
      line-height: 47px;
      font-family: monospace;
      text-shadow: 5px 4px 3px #0a192f;
   }

   .title {
      color: #ffffff;
      margin-top: 14px;
      font-size: 1.8rem;
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

   .skills {
      margin-top: 120px;
   }

   footer,
   .contact,
   .projects {
      margin-top: 120px;
   }

   .project {
      padding: 17px;
      margin-top: 30px;
      border: 1px solid #8892b0;
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
      font-size: 1.2rem;
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
      background-color: #0a192f;
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
      font-size: 1.2rem;
      font-weight: bold;
      letter-spacing: 1px;
   }

   .contact__desc {
      margin-top: 28px;
      margin-bottom: 10px;
   }

   .email {
      letter-spacing: 1px;
   }

   @media screen and (min-width: 770px) {
      p {
         line-height: 26px;
         font-size: calc(1.2rem + 0.1px - 2px);
      }
   }
</style>

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
         Currently, i am working for my personal project, and that project i use
         often when i make some application.
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
         <li>Sapper</li>
         <li>Vuejs</li>
         <li>Git</li>
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
            rel="noopener">my-STYLE</a>

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
            rel="noopener">svelte-social-media</a>

         <p class="project__desc">
            Make clone social media using Svelte, Sapper and Firebase.
         </p>

         <span class="project__tech">Svelte</span>
         <span class="project__tech">Sapper</span>
      </div>

      <div class="project">
         <a
            href="https://github.com/apriliandi246/quran"
            target="_blank"
            class="project__title"
            rel="noopener">read-quran</a>

         <p class="project__desc">
            Web application that allow you read Quran, read the interpretation
            and you can listen too.
         </p>

         <span class="project__tech">Vuejs</span>
      </div>

      <div class="project">
         <a
            href="https://github.com/apriliandi246/vscode-css-sort"
            target="_blank"
            class="project__title"
            rel="noopener">vscode-css-sort</a>

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
         <p>More projects</p>
      </a>
   </section>

   <section class="contact">
      <h1 class="title">My Contact</h1>
      <div class="line" />

      <p class="contact__desc">
         I am often active on Twitter, but you can also contact me via E-mail.
      </p>

      <ul>
         <li class="email">apriliandi642@gmail.com</li>
         <li>
            <a
               href="https://twitter.com/calon_jenazah__"
               target="_blank"
               rel="noopener">My Twitter account</a>
         </li>
      </ul>
   </section>

   <footer>
      <div class="line-2" />
      <p>💚</p>
      <div class="line-2" />
   </footer>
</div>

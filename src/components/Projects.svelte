<section class="projects">
   <h1 class="projects__title">My Projects</h1>
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
         href="https://github.com/apriliandi246/vscode-css-sort"
         target="_blank"
         class="project__title"
         rel="noopener">vscode-css-sort</a
      >

      <p class="project__desc">
         Visual Studio Code extension for make your css properties sorted, and
         make it easy to read.
      </p>

      <span class="project__tech">vscode-extension</span>
      <span class="project__tech">Typescript</span>
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
         Web application that allow you read Quran, read the interpretation and
         you can listen too.
      </p>

      <span class="project__tech">Vue</span>
   </div>

   <a
      href="https://github.com/apriliandi246"
      target="_blank"
      rel="noopener"
      class="project__more"
   >
      <img src="/github.png" alt="github" />
      <p class="more-project">More projects</p>
   </a>
</section>

<style>
   .projects {
      margin-top: 140px;
   }

   .projects__title {
      color: #ffffff;
      font-size: 1.2rem;
      font-weight: bold;
      line-height: 44px;
      margin-bottom: 5px;
      letter-spacing: 1.2px;
      font-family: monospace;
   }

   .line {
      height: 3px;
      width: 250px;
      border-radius: 10px;
      margin-bottom: 40px;
      background-color: #8892b0;
   }

   .project {
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 55px;
      border: 2px solid #8892b0;
      background-color: #2e1f3b;
      box-shadow: 11px 11px 1px 1px #8892b0;
   }

   .project__title {
      color: #ccd8e2;
      font-size: 1.1rem;
      font-weight: bold;
      text-decoration: none;
      font-family: monospace;
   }

   .project__desc {
      margin-top: 20px;
      font-size: 1rem;
      color: #ffffff;
      font-family: monospace;
      line-height: 25px;
   }

   .project__tech {
      padding: 12px;
      color: #ccd8e2;
      margin-top: 20px;
      font-size: 1rem;
      font-weight: bold;
      margin-right: 10px;
      border-radius: 20px;
      display: inline-block;
      font-family: monospace;
      background-color: #162131;
   }

   .project__more {
      display: flex;
      padding: 15px;
      cursor: pointer;
      margin-top: 40px;
      align-items: center;
      border-radius: 100px;
      text-decoration: none;
      justify-content: center;
      background-color: #2e1f3b;
      border: 3px solid #8892b0;
   }

   .project__more img {
      margin-right: 15px;
   }

   .project__more p {
      color: #ccd8e2;
      font-size: 1rem;
      font-weight: bold;
      letter-spacing: 1px;
      font-family: monospace;
   }

   .project__title:hover {
      color: #7488a5;
      text-decoration: underline;
   }

   .project__more:hover {
      background-color: #162131;
   }

   @media screen and (min-width: 770px) {
      .project__desc {
         line-height: 30px;
      }
   }

   @media screen and (min-width: 1200px) {
      .project__desc,
      .project__tech {
         font-size: 0.9rem;
      }
   }
</style>

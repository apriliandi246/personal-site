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
      color: #ccd8e2;
      margin-top: 17px;
      font-size: 1.3rem;
      font-weight: bold;
      margin-right: 20px;
      display: inline-block;
      font-family: monospace;
   }

   ul li::before {
      width: 1em;
      content: "\00BB";
      margin-left: 1px;
      font-weight: bold;
      display: inline-block;
      color: rgb(141, 175, 206);
   }

   .container {
      width: 100%;
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
      line-height: 44px;
      font-family: monospace;
   }

   .title {
      color: #ffffff;
      margin-top: 14px;
      font-size: 1.8rem;
      font-weight: bold;
      line-height: 44px;
      letter-spacing: 1.2px;
      font-family: monospace;
   }

   .about__desc-1 {
      color: #ccd8e2;
      margin-top: 20px;
   }

   .about__desc-2 {
      margin-top: 10px;
   }

   .skills__desc {
      margin-top: 28px;
   }

   .skills {
      margin-top: 120px;
   }

   .line {
      height: 2px;
      width: 170px;
      border-radius: 30%;
      background-color: #8892b0;
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
         often.
      </p>
   </section>

   <section class="skills">
      <h1 class="title">Skills</h1>
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
</div>

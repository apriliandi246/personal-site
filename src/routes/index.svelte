<style>
   main {
      height: 100vh;
      overflow-y: auto;
      scroll-snap-type: y mandatory;
      -webkit-overflow-scrolling: touch;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
         Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
   }

   .section {
      height: 100vh;
      scroll-snap-align: start;
      transition: scroll-snap-align 0.2s;
   }

   .section-1 {
      display: flex;
      align-items: center;
      flex-direction: column;
      justify-content: center;
      background-color: #e7ddde;
   }

   .section-1__title {
      color: #332c2c;
      font-weight: bold;
      font-size: 2.1rem;
      font-family: monospace;
   }

   .section-1__emoji {
      font-size: 2rem;
      margin-top: 30px;
   }

   .section-2 {
      padding: 30px;
      text-align: left;
      background: linear-gradient(
         360deg,
         rgba(2, 0, 36, 1) 0%,
         rgba(48, 30, 60, 1) 0%
      );
   }

   .section-2__emoji {
      font-size: 2.1rem;
      margin-bottom: 10px;
   }

   .section-2__title {
      color: #ffffff;
      font-weight: bold;
      font-size: 1.8rem;
      line-height: 37px;
      margin-block: 15px;
      letter-spacing: 1px;
   }

   .section-2__title span {
      color: #e9774d;
      font-weight: 500;
      display: inline-block;
      letter-spacing: 1.5px;
   }

   .section-2__desc {
      color: #ffffff;
      font-size: 1.2rem;
      line-height: 26px;
      letter-spacing: 1.2px;
   }

   .section-3 {
      display: flex;
      text-align: center;
      align-items: center;
      flex-direction: column;
      justify-content: center;
      background-color: #dbc798;
   }

   .section-3 a {
      transition: transform 0.2s;
   }

   .section-3 a:hover {
      transform: scale(1.1);
   }

   .section-3__title {
      color: #080808;
      margin-top: 25px;
      font-weight: bold;
      font-size: 1.5rem;
      line-height: 24px;
      padding-inline: 70px;
      font-family: monospace;
   }

   .section-3__img {
      width: 90px;
      height: 90px;
   }

   .section-4 {
      display: flex;
      align-items: center;
      flex-direction: column;
      background-color: #cac7bc;
      justify-content: space-evenly;
   }

   .section-4 img {
      width: 50px;
      height: 50px;
      cursor: pointer;
   }

   .section-4 a,
   .section-4 div {
      display: flex;
      align-items: center;
      text-decoration: none;
      flex-direction: column;
      justify-content: center;
   }

   .section-4 p {
      color: #461717;
      margin-top: 20px;
      font-weight: 550;
      font-size: 1.2rem;
      letter-spacing: 1.2px;
   }

   .section-4 a img {
      transition: transform 0.2s;
   }

   .section-4 a img:hover {
      transform: scale(1.2);
   }

   .section-5 {
      display: flex;
      align-items: center;
      justify-content: center;
      background-color: #2b3036;
   }

   .section-5__title {
      color: #ffffff;
      font-weight: bold;
      font-size: 2.5rem;
      font-family: monospace;
   }
</style>

<svelte:head>
   <title>Apriliandi</title>
</svelte:head>

<main>
   <section class="section section-1">
      <h1 class="section-1__title">👋 Hai there....</h1>
      <p class="section-1__emoji">👇</p>
   </section>

   <section class="section section-2">
      <h1 class="section-2__emoji">👨‍💻</h1>
      <h1 class="section-2__title">
         My name is
         <br /><span>Farhan Apriliandi</span>
      </h1>
      <p class="section-2__desc">
         💻 I'm self taught programmer focus on Front-End
      </p>
   </section>

   <section class="section section-3">
      <a href="https://github.com/apriliandi246" target="_blank" rel="noopener">
         <img src="/github.png" class="section-3__img" alt="github-icon" />
      </a>
      <h1 class="section-3__title">
         You can see all my personal projects in my Github account
      </h1>
   </section>

   <section class="section section-4">
      <a href="https://github.com/apriliandi246" target="_blank" rel="noopener">
         <img src="/github.png" alt="my-github" />
         <p>@apriliandi246</p>
      </a>

      <div class="email">
         <img src="/email.png" alt="my-email" />
         <p>apriliandi642@gmail.com</p>
      </div>

      <a
         href="https://www.linkedin.com/in/farhan-apriliandi-934442191/"
         target="_blank"
         rel="noopener">
         <img src="/linkedin.png" alt="my-linkedin" />
         <p>Farhan Apriliandi</p>
      </a>

      <a
         href="https://twitter.com/calon_jenazah__"
         target="_blank"
         rel="noopener">
         <img src="/twitter.png" alt="my-twitter" />
         <p>@calon_jenazah__</p>
      </a>
   </section>

   <section class="section section-5">
      <h1 class="section-5__title">👋 Bye....</h1>
   </section>
</main>

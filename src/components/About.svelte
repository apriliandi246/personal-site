<section class="about">
   <h1 class="about__title">About Me</h1>
   <div class="line" />

   <h1 class="about__intro">Hi, I am</h1>
   <h1 class="about__name">Farhan Apriliandi</h1>
   <p class="about__desc">
      I'm self-taught programmer who focuses on Front-End 👨‍💻 <br /><br /> Currently,
      i am working for my personal projects and that project focus on front-end (web
      application or some tools)
   </p>
</section>

<style>
   .about__title {
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

   .about__desc {
      color: #ffffff;
      font-size: 1rem;
      margin-top: 20px;
      line-height: 28px;
      font-family: monospace;
   }

   .about__intro {
      color: #ccd8e2;
      margin-top: 30px;
      font-size: 1.3rem;
      font-family: monospace;
   }

   .about__name {
      color: #7488a5;
      font-size: 2rem;
      margin-top: 14px;
      line-height: 47px;
      font-weight: bold;
      font-family: monospace;
      text-shadow: 2px 2px #3b6b86;
   }

   @media screen and (min-width: 770px) {
      .about__desc {
         line-height: 30px;
      }
   }

   @media screen and (min-width: 1200px) {
      .about__desc {
         font-size: 0.9rem;
      }
   }
</style>

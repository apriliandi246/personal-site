<svelte:head>
   <title>What I think about Svelte</title>
   <meta
      name="description"
      content="We know that the growing of Javascript is very fast. Maybe today you learn
   some Javascript framework, but maybe next month or even next day will come
   out another framework (ahhh sh*t here we go again). I think we as a
   Javascript developer have a lot of option to choose some tools that useful for us"
   />
</svelte:head>

<a href="/blog" class="back">🏃 Back</a>

<h1 class="title">What I think about Svelte</h1>

<span class="date">2021-02-28</span>

<p>
   We know that the growing of Javascript is very fast. Maybe today you learn
   some Javascript framework, but maybe next month or even next day will come
   out another framework (ahhh sh*t here we go again). I think we as a
   Javascript developer have a lot of option to choose some tools that useful
   for us
</p>

<p>
   One of the Javascript framework that very interesting to me that is Svelte.
   Svelte is a Javascript frontend framework to build a user interface in a
   declarative way, like React or Vue. But, I think Svelte more than that.
   Basically, Svelte compiles your code to optimize Javascript code, Svelte will
   not bring the Svelte code itself to the browser, and the browser just
   receives the optimized Javascript code. I think the keyword "optimize" what I
   mentioned before will make sense to you if you know basic how Svelte compiles
   your code. Check out <a
      href="https://lihautan.com/compile-svelte-in-your-head-part-1/"
      rel="noopener"
      target="_blank">this blog</a
   >, it's a very cool article.
</p>

<p>
   Another advantage from Svelte is you will get a small bundle code and the
   performance is not inferior to the other framework, even Svelte has better
   performance in some situations (or even all situations). If you have a web
   application that is every part using another framework, for example, in the
   search bar using Vue or another part using React. Using Svelte is very easy
   to use in this situation because Svelte compiles your code to vanilla
   Javascript and lastly, you just link to the HTML code. If you want to learn
   more about the performance, I recommend you watch <a
      href="https://www.youtube.com/watch?v=AdNJ3fydeao"
      rel="noopener"
      target="_blank">this video</a
   >.
</p>

<p>
   What about developer experience???? Personally, I really like the developer
   experience at Svelte because I feel like I'm going back to when I first
   started learning web development, just HTML, CSS, and Javascript code without
   any fancy API or syntax that will make you confuse (use the platform).
</p>

<p>
   One of my favorite features from Svelte is scoped style, that's mean your
   style just affected to file itself and will not be affected other files, and
   unused style, that's mean if you have a lot of CSS code and maybe one of your
   code is unused CSS code, and Svelte will warn you and you can easily remove
   it without see the HTML code and come back to CSS code again.
</p>

<p>
   I will not show you some Svelte code because you can directly go to the <a
      href="http://svelte.dev/"
      rel="noopener"
      target="_blank">documentation</a
   >
   and try yourself and feel some magic from it.
   <b class="text__bold"
      >Because in this blog I just give you what I think about Svelte. And
      Svelte help me a lot when I wanna built some complex frontend app without
      learning any framework with fancy API or syntax that will make me a
      headache and even sometimes I have to install another library to make my
      code work very well.</b
   >
</p>

<p>Summary, just choose tool that you neeed or useful for you</p>

<p>Yeahh, that is what I think about Svelte.... Thanks Svelte 🙏</p>

<style>
   .back {
      color: #ffffff;
      font-size: 1.5rem;
      margin-bottom: 70px;
      display: inline-block;
      text-decoration: none;
      font-family: monospace;
   }

   .title {
      color: #ffffff;
      font-size: 1.5rem;
      line-height: 34px;
      font-weight: bold;
      margin-bottom: 20px;
      letter-spacing: 1.2px;
      font-family: monospace;
   }

   .date {
      color: #b6b8bd;
      font-size: 1rem;
      margin-bottom: 44px;
      display: inline-block;
      font-family: monospace;
   }

   p {
      color: #ffffff;
      font-size: 1rem;
      line-height: 27px;
      margin-bottom: 30px;
      font-family: monospace;
   }

   p a {
      color: #737d8a;
   }

   .text__bold {
      font-weight: bold;
   }

   @media screen and (min-width: 770px) {
      p {
         line-height: 28px;
      }
   }

   @media screen and (min-width: 1200px) {
      p,
      .date {
         font-size: 0.9rem;
      }
   }
</style>

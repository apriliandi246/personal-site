<svelte:head>
   <title>Blog</title>
   <meta
      name="description"
      content="Hi, I'm Farhan Apriliandi, I'm a self-taught programmer who focuses on web development especially on front-end and currently, i am working for my personal projects and that project focus
      on front-end (web application or some tools) 👨‍💻👨‍💻👨‍💻"
   />
</svelte:head>

<a href="/" class="home">🏠</a>

<div class="articles">
   <div class="article">
      <a href="/blog/my-first-vscode-extension" class="article__title"
         >My first Vscode extension</a
      >
      <span class="article__date">2021-03-01</span>
   </div>

   <div class="article">
      <a href="/blog/what-i-think-about-svelte" class="article__title"
         >What I think about Svelte</a
      >
      <span class="article__date">2021-02-28</span>
   </div>

   <div class="article">
      <a href="/blog/the-phenomena-of-should-i-learn" class="article__title"
         >The phenomenon of "SHOULD I LEARN"</a
      >
      <span class="article__date">2021-02-25</span>
   </div>
</div>

<style>
   .home {
      cursor: pointer;
      font-size: 1.4rem;
      margin-bottom: -20px;
      display: inline-block;
      text-decoration: none;
   }

   .articles {
      color: #ffffff;
      margin-top: 50px;
   }

   .article {
      margin-bottom: 46px;
   }

   .article__title {
      color: #ffffff;
      font-size: 1.1rem;
      line-height: 30px;
      margin-bottom: 10px;
      letter-spacing: 1px;
      display: inline-block;
      text-decoration: none;
      font-family: monospace;
   }

   .article__title:hover {
      color: #8892b0;
      text-decoration: underline;
   }

   .article__date {
      display: block;
      color: #b6b8bd;
      font-size: 1rem;
      letter-spacing: 1.4px;
      font-family: monospace;
   }

   @media screen and (min-width: 1200px) {
      .article__date {
         font-size: 0.9rem;
      }
   }
</style>

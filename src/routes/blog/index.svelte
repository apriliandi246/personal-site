<svelte:head>
   <title>Blog</title>
</svelte:head>

<div class="container">
   <a href="/" class="home">🏠</a>

   <div class="articles">
      <div class="article">
         <a href="/blog/the-phenomena-of-should-i-learn" class="article__title"
            >The phenomenon of "SHOULD I LEARN"</a
         >
         <span class="article__date">2021-02-25</span>
      </div>
   </div>
</div>

<style>
   .container {
      width: 82%;
      font-family: monospace;
      margin: 40px auto 45px auto;
   }

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
      margin-bottom: 55px;
   }

   .article__title {
      color: #ffffff;
      font-size: 1.1rem;
      line-height: 30px;
      margin-bottom: 10px;
      letter-spacing: 1px;
      display: inline-block;
      text-decoration: none;
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
   }

   @media screen and (min-width: 815px) {
      .container {
         width: 76%;
      }
   }

   @media screen and (min-width: 960px) {
      .container {
         width: 70%;
      }
   }

   @media screen and (min-width: 1015px) {
      .container {
         width: 63%;
      }
   }

   @media screen and (min-width: 1200px) {
      .container {
         width: 55%;
      }
   }

   @media screen and (min-width: 1360px) {
      .container {
         width: 50%;
      }
   }

   @media screen and (min-width: 1520px) {
      .container {
         width: 45%;
      }
   }

   @media screen and (min-width: 1700px) {
      .container {
         width: 40%;
      }
   }

   @media screen and (min-width: 1830px) {
      .container {
         width: 40%;
      }
   }

   @media screen and (min-width: 1870px) {
      .container {
         width: 38%;
      }
   }
</style>

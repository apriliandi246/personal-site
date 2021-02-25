<section class="rest">
   <h1 class="rest__title">Another Things</h1>
   <div class="line" />

   <ul>
      <li>
         <a href="/blog">Blog</a>
      </li>
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
            rel="noopener">LinkedIn</a
         >
      </li>
      <li class="email">apriliandi642@gmail.com</li>
   </ul>
</section>

<style>
   .rest {
      margin-top: 140px;
   }

   .rest__title {
      color: #ffffff;
      margin-top: 14px;
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

   ul {
      display: flex;
      flex-direction: column;
   }

   ul li {
      padding: 13px;
      color: #ffffff;
      margin-bottom: 30px;
      font-size: 1rem;
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
      width: 1.2em;
      color: #ffffff;
      content: "\25C7";
      margin-left: 2px;
      font-weight: bold;
      display: inline-block;
   }

   @media screen and (min-width: 1200px) {
      li a {
         font-size: 0.9rem;
      }
   }
</style>

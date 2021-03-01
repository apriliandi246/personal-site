<svelte:head>
   <title>My first Vscode extension</title>
</svelte:head>

<a href="/blog" class="back">🏃 Back</a>

<h1 class="title">My first Vscode extension</h1>

<span class="date">2021-03-01</span>

<p>
   We know that Vscode is the most popular text editor for programmers. A lot of
   features we can use in Vscode and one of my favorite features is Vscode
   extensions. We can use useful extensions for our productivity like code
   formatted, linter, syntax highlighting, and more.
</p>

<p>
   But, why not try to make our Vscode extension to solve our problem. Yeah, a
   couple of months ago I published my first Vscode extensions. It's just a
   simple extension but it solves my problem. Basically, my problem is when I
   write CSS code and after that, I read the code, but I'm more comfortable when
   the CSS properties are sorted, it makes me enjoy especially when I read the
   code.
</p>

<h1 class="css-title">Before :</h1>

<pre>
   <code>
   .component {"{"}
   white-space: pre-line;
   display: block;
   resize: none;
   font-family: monospace;
   width: 100%;
   padding: 15px;
   border: 1px solid #38444d;
   font-size: 18px;
   outline: none;
   transition: background-color 0.2s;
   box-sizing: border-box;
   background-color: #253341;
   margin-top: 17px;
   color: #f5f5f5;
{"}"}
   </code>
</pre>

<h1 class="css-title">Smaller to Bigger :</h1>

<pre>
   <code>
   .component {"{"}
   width: 100%;
   resize: none;
   padding: 15px;
   outline: none;
   display: block;
   color: #f5f5f5;
   font-size: 18px;
   margin-top: 17px;
   white-space: pre-line;
   font-family: monospace;
   box-sizing: border-box;
   border: 1px solid #38444d;
   background-color: #253341;
   transition: background-color 0.2s;
{"}"}
   </code>
</pre>

<h1 class="css-title">Bigger to Smaller :</h1>

<pre>
   <code>
   .component {"{"}
   transition: background-color 0.2s;
   border: 1px solid #38444d;
   background-color: #253341;
   font-family: monospace;
   box-sizing: border-box;
   white-space: pre-line;
   margin-top: 17px;
   font-size: 18px;
   display: block;
   color: #f5f5f5;
   padding: 15px;
   outline: none;
   resize: none;
   width: 100%;
{"}"}
   </code>
</pre>

<p>
   Before I create the extension, I have to manually sort all of the properties.
   And after that, I build a web application to handle this. But I'm so lazy to
   switch from the text editor to the browser and come back again to the text
   editor. That is why I build this extension.
</p>

<p>
   You can check the code in my Github repository (<a
      href="https://github.com/apriliandi246/CSS-sort"
      rel="noopener"
      target="_blank">the web version</a
   >
   or
   <a
      href="https://github.com/apriliandi246/vscode-css-sort"
      rel="noopener"
      target="_blank">the Vscode extension version</a
   >). And you can see all my solutions for sorting CSS properties from this
   repository.
</p>

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

   .css-title {
      color: #ffffff;
      font-size: 1.1rem;
      line-height: 34px;
      font-weight: bold;
      margin-top: 30px;
      margin-bottom: 20px;
      letter-spacing: 1.2px;
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

   pre {
      padding: 20px;
      margin-bottom: 70px;
      border-radius: 10px;
      border: 2px solid #8892b0;
      background-color: #2e1f3b;
      box-shadow: 11px 11px 1px 1px #8892b0;
   }

   code {
      font-size: 1rem;
      color: #e5ebde;
      font-weight: 550;
      line-height: 25px;
      font-family: monospace;
   }

   @media screen and (min-width: 770px) {
      p {
         line-height: 28px;
      }
   }

   @media screen and (min-width: 1200px) {
      p,
      code,
      .date {
         font-size: 0.9rem;
      }
   }
</style>

<script>
   import { fade } from "svelte/transition";
</script>

<style>
   nav {
      display: flex;
      margin-top: 20px;
      margin-right: 24px;
      align-items: center;
      justify-content: flex-end;
   }

   .github_icon {
      width: 25px;
      height: 25px;
      transition: transform 0.2s;
   }

   .linkedin_icon {
      width: 22px;
      height: 22px;
      transition: transform 0.2s;
   }

   .twitter_icon {
      width: 42px;
      height: 42px;
      margin-inline: 28px;
      transition: transform 0.2s;
   }

   .line-1,
   .line-2 {
      width: 50px;
      height: 3px;
      border-radius: 20px;
      background-color: #8892b0;
   }

   .line-1 {
      margin-right: 18px;
   }

   .line-2 {
      margin-left: 18px;
   }

   .github_icon:hover,
   .twitter_icon:hover,
   .linkedin_icon:hover {
      transform: scale(1.2);
   }
</style>

<nav in:fade={{ duration: 500 }}>
   <div class="line-1" />
   <a href="https://github.com/apriliandi246" target="_blank" rel="noopener">
      <img class="github_icon" src="/github.png" alt="github" />
   </a>
   <a href="https://twitter.com/calon_jenazah__" target="_blank" rel="noopener">
      <img class="twitter_icon" src="/twitter.png" alt="twitter" />
   </a>
   <a
      href="https://www.linkedin.com/in/farhan-apriliandi-934442191/"
      target="_blank"
      rel="noopener">
      <img class="linkedin_icon" src="/linkedin.png" alt="linkedin" />
   </a>
   <div class="line-2" />
</nav>

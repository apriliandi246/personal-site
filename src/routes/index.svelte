<script>
   import { onMount } from "svelte";
   import { fade } from "svelte/transition";
   import Bouncer from "../components/Bouncer.svelte";
   import LineSide from "./../components/LineSide.svelte";
   import About from "../components/About.svelte";
   import Projects from "../components/Projects.svelte";
   import Rest from "../components/Rest.svelte";
   import Footer from "../components/Footer.svelte";

   let isReady = false;

   onMount(() => {
      const consoleSignatureStyle =
         "font-size: 16px;" +
         "background: linear-gradient(to right, #e66465, #9198e5);" +
         "color: white;" +
         "text-align: center;" +
         "padding: 10px 15px;" +
         "width: 100%;" +
         "border-radius: 20px;" +
         "font-weight: bold;";

      const consoleSignatureText = "%cHy there! 👋";
      console.log(consoleSignatureText, consoleSignatureStyle);

      setTimeout(() => {
         isReady = true;
      }, 2300);
   });
</script>

<svelte:head>
   <title>Apriliandi</title>
</svelte:head>

{#if isReady === false}
   <Bouncer />
{/if}

{#if isReady === true}
   <div class="container" in:fade={{ duration: 500 }}>
      <LineSide />
      <About />
      <Projects />
      <Rest />
      <Footer />
      <LineSide />
   </div>
{/if}

<style>
   .container {
      width: 82%;
      margin: 40px auto 45px auto;
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

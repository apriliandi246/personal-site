<script>
   import { onMount } from "svelte";
   import { showModal } from "../store";
   import { fade } from "svelte/transition";
   import Nav from "../components/Nav.svelte";
   import Modal from "../components/Modal.svelte";
   import Bouncer from "../components/Bouncer.svelte";
   import Introdcution from "../components/Content.svelte";

   let isReady = false;

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

   onMount(() => {
      setTimeout(() => {
         isReady = true;
      }, 2900);
   });
</script>

<svelte:head>
   <title>apriliandi</title>
</svelte:head>

{#if isReady === false}
   <Bouncer />
{/if}

{#if isReady === true && $showModal === true}
   <Modal />
{/if}

{#key isReady}
   {#if isReady === true}
      <div class="container" in:fade={{ duration: 500 }}>
         <Nav />
         <Introdcution />
         <Nav />
      </div>
   {/if}
{/key}

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

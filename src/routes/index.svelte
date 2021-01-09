<script>
   import { onMount } from "svelte";
   import { fade } from "svelte/transition";
   import Nav from "../components/Nav.svelte";
   import Bouncer from "../components/Bouncer.svelte";
   import Introdcution from "../components/Content.svelte";

   let isReady = false;

   onMount(() => {
      setTimeout(() => {
         isReady = true;
      }, 2300);
   });
</script>

<style>
   .container {
      width: 82%;
      margin: 80px auto 45px auto;
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

<svelte:head>
   <title>Apriliandi</title>
</svelte:head>

{#if isReady === false}
   <Bouncer />
{/if}

{#key isReady}
   {#if isReady === true}
      <Nav />

      <div class="container" in:fade={{ duration: 400 }}>
         <Introdcution />
      </div>
   {/if}
{/key}

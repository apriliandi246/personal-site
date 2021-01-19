<script>
   import { showModal } from "../store";
   import { scale } from "svelte/transition";
</script>

<div
   class="modal"
   transition:scale={{ duration: 350 }}
   on:click|self={() => ($showModal = false)}
>
   <div class="modal__body">
      <h1 class="modal__head">😀</h1>
      <p class="modal__content">👌 Email copied....</p>
      <div class="modal__footer">
         <button
            on:click={() => ($showModal = false)}
            class="modal__cancel-button">Close</button
         >
      </div>
   </div>
</div>

<style>
   .modal {
      top: 0;
      left: 0;
      z-index: 1;
      width: 100%;
      height: 100%;
      position: fixed;
      background-color: #0e020266;
   }

   .modal__body {
      width: 100%;
      padding: 20px;
      color: #ffffff;
      margin: 40% auto;
      position: relative;
      box-sizing: border-box;
      background-color: #2e1f3b;
      border-top: 3px solid #8892b0;
      border-bottom: 3px solid #8892b0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
         Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
   }

   .modal__head {
      font-size: 1.7rem;
      font-weight: bold;
      word-wrap: break-word;
   }

   .modal__content {
      margin-top: 25px;
      font-size: 1.3rem;
      margin-bottom: 25px;
      letter-spacing: 0.8px;
      word-wrap: break-word;
   }

   .modal__footer {
      text-align: right;
   }

   .modal__cancel-button {
      outline: none;
      padding: 10px;
      color: #ffffff;
      cursor: pointer;
      font-size: 1rem;
      font-weight: bold;
      border-radius: 10px;
      letter-spacing: 1.2px;
      box-sizing: border-box;
      border: 3px solid #8892b0;
      background-color: #0a192f;
      transition: transform 0.2s;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
         Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
   }

   .modal__cancel-button:hover {
      transform: scale(1.03);
   }

   @media screen and (min-width: 600px) {
      .modal__body {
         margin: 30% auto;
      }
   }

   @media screen and (min-width: 650px) {
      .modal__body {
         width: 92%;
         border-radius: 10px;
         border: 3px solid #8892b0;
      }
   }

   @media screen and (min-width: 700px) {
      .modal__body {
         width: 84%;
         margin: 27% auto;
      }
   }

   @media screen and (min-width: 760px) {
      .modal__cancel-button {
         font-size: 0.9rem;
      }
   }

   @media screen and (min-width: 820px) {
      .modal__body {
         width: 75%;
         margin: 23% auto;
      }
   }

   @media screen and (min-width: 920px) {
      .modal__body {
         width: 70%;
         margin: 22% auto;
      }
   }

   @media screen and (min-width: 990px) {
      .modal__body {
         width: 60%;
         margin: 22% auto;
      }
   }

   @media screen and (min-width: 1060px) {
      .modal__body {
         width: 56%;
         margin: 20% auto;
      }
   }

   @media screen and (min-width: 1090px) {
      .modal__body {
         width: 51%;
         margin: 19% auto;
      }
   }

   @media screen and (min-width: 1200px) {
      .modal__body {
         width: 51%;
         margin: 19% auto;
      }

      .modal__head {
         font-size: 1.4rem;
      }
   }

   @media screen and (min-width: 1250px) {
      .modal__body {
         width: 48%;
         margin: 16% auto;
      }
   }

   @media screen and (min-width: 1340px) {
      .modal__body {
         width: 47%;
         margin: 14% auto;
      }
   }

   @media screen and (min-width: 1480px) {
      .modal__body {
         width: 43%;
         margin: 13% auto;
      }
   }

   @media screen and (min-width: 1560px) {
      .modal__body {
         width: 39%;
         margin: 13% auto;
      }
   }

   @media screen and (min-width: 1701px) {
      .modal__body {
         width: 36%;
         margin: 12% auto;
      }
   }

   @media screen and (min-width: 1850px) {
      .modal__body {
         width: 34%;
         margin: 12% auto;
      }
   }

   @media screen and (min-width: 1900px) {
      .modal__body {
         width: 32%;
         margin: 12% auto;
      }
   }
</style>

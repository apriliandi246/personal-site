<script>
   import { fade } from "svelte/transition";
</script>

<style>
   .bouncer-1 {
      top: 50%;
      left: 50%;
      width: 115px;
      display: flex;
      height: 100px;
      position: absolute;
      align-items: center;
      margin: -60px 0 0 -60px;
      justify-content: space-between;
   }

   .bouncer-1 .ball {
      width: 18px;
      height: 18px;
      border-radius: 100%;
      background-color: #faf1f1;
      animation: bouncer 0.5s cubic-bezier(0.19, 0.57, 0.3, 0.98) infinite
         alternate;
   }

   .bouncer-1 .ball:nth-child(2) {
      animation-delay: 0.1s;
   }

   .bouncer-1 .ball:nth-child(3) {
      animation-delay: 0.2s;
   }

   .bouncer-1 .ball:nth-child(3) {
      animation-delay: 0.3s;
   }

   .bouncer-1 .ball:nth-child(4) {
      animation-delay: 0.4s;
   }

   @keyframes bouncer {
      from {
         transform: translateY(0);
      }

      to {
         transform: translateY(-100px);
      }
   }
</style>

<div class="bouncer-1" out:fade={{ duration: 200 }}>
   <div class="ball" />
   <div class="ball" />
   <div class="ball" />
   <div class="ball" />
</div>

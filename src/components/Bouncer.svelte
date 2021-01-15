<script>
   import { fade } from "svelte/transition";
</script>

<div class="bouncer" out:fade={{ duration: 200 }}>
   <div class="bouncer_ball" />
   <div class="bouncer_ball" />
   <div class="bouncer_ball" />
   <div class="bouncer_ball" />
</div>

<style>
   .bouncer {
      top: 52%;
      left: 50%;
      width: 109px;
      display: flex;
      height: 100px;
      position: absolute;
      align-items: center;
      margin-left: -60px;
      justify-content: space-between;
   }

   .bouncer_ball {
      width: 18px;
      height: 18px;
      border-radius: 100%;
      background-color: #faf1f1;
      animation: bouncer 0.5s cubic-bezier(0.19, 0.57, 0.3, 0.98) infinite
         alternate;
   }

   .bouncer_ball:nth-child(2) {
      animation-delay: 0.1s;
   }

   .bouncer_ball:nth-child(3) {
      animation-delay: 0.2s;
   }

   .bouncer_ball:nth-child(3) {
      animation-delay: 0.3s;
   }

   .bouncer_ball:nth-child(4) {
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

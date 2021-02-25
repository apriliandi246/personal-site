<div class="container">
   <div class="right">
      <div class="line-3" />
      <div class="line-2" />
      <div class="line-1" />
   </div>

   <div class="left">
      <div class="line-3" />
      <div class="line-2" />
      <div class="line-1" />
   </div>
</div>

<style>
   .container {
      display: flex;
      margin-bottom: 60px;
      align-items: center;
      justify-content: space-between;
   }

   .right {
      display: flex;
      margin-bottom: 10px;
      align-items: flex-start;
      flex-direction: column;
   }

   .left {
      display: flex;
      margin-bottom: 10px;
      align-items: flex-end;
      flex-direction: column;
   }

   .line-1,
   .line-2,
   .line-3 {
      border-radius: 20px;
      margin-bottom: 10px;
      background-color: #8892b0;
   }

   .line-1 {
      width: 60px;
      height: 4px;
   }

   .line-2 {
      width: 90px;
      height: 4px;
   }

   .line-3 {
      width: 120px;
      height: 4px;
   }
</style>

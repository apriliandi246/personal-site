<script>
   export let status;
   export let error;
</script>

<svelte:head>
   <title>{status}</title>
</svelte:head>

<div class="container">
   <h1>{status}</h1>
   <p>{error.message}</p>
   <a href="/">Back</a>
</div>

<style>
   .container {
      display: flex;
      color: #ffffff;
      margin-top: 140px;
      align-items: center;
      flex-direction: column;
   }

   h1 {
      font-size: 5rem;
      margin-top: 14px;
      font-weight: bold;
      letter-spacing: 4px;
      font-family: monospace;
   }

   p {
      font-size: 1.9rem;
      margin-block: 20px;
      font-family: monospace;
   }

   a {
      color: #ffffff;
      font-size: 1.5rem;
      font-family: monospace;
   }

   a:hover {
      color: #7488a5;
   }
</style>

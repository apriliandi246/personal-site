<script>
   import { onMount } from "svelte";
   import Rest from "../components/Rest.svelte";
   import About from "../components/About.svelte";
   import Footer from "../components/Footer.svelte";
   import Projects from "../components/Projects.svelte";
   import LineSide from "./../components/LineSide.svelte";

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
   });
</script>

<svelte:head>
   <title>Hi, I'm Farhan Apriliandi</title>
   <meta
      name="description"
      content="Hi, I'm Farhan Apriliandi, I'm a self-taught programmer who focuses on web development especially on front-end and currently, i am working for my personal projects and that project focus
      on front-end (web application or some tools) 👨‍💻👨‍💻👨‍💻"
   />
</svelte:head>

<LineSide />

<About />

<Projects />

<Rest />

<Footer />

<LineSide />

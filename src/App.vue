<template>
  <div id="app" class="flex flex-col bg-gray-100">
  <div class="container mx-auto">
    <h1 class="font-title text-4xl leading-none pt-4 pb-12">Monocle</h1>
    <section>
      <h1 class="text-4xl leading-none">Minimalist and <span class="relative highlight">productivity-focused</span> <br /> news reader.</h1>
      <div class="flex flex-row mt-4">
      <div class="flex flex-col">
      <button class="w-56 tracking-widest py-1 text-xl rounded uppercase bg-gray-900 text-gray-100 border-gray-900">Buy</button>
      </div>
      <button class="ml-4 w-56 tracking-widest py-1 text-xl rounded bg-white text-gray-900 border-gray-900 shadow">Import OPML</button>
      </div>
    </section>
    <small>$49 one-time payment</small>
    <img src="https://freesvg.org/img/1418949122.png" class="w-10/12 mx-auto py-12" >
    <section class="flex flex-col justify-center items-center text-center">
      <p>Stop endlessly scrolling the web. <br />Start your <span class="font-bold highlight">information diet</span> right now</p>
      <button class="mt-4 w-56 py-1 text-xl rounded uppercase bg-gray-900 text-gray-100 border-gray-900">Buy now</button>
      <small class="text-xs text-gray-500"><b>$49</b> one-time payment</small>
    </section>
    <section class="flex flex-row flex-wrap mt-12">
      <div class="w-1/3 px-4 py-8">
        <h3 class="font-bold mt-4">Desktop First</h3>
        <p class="font-thin mt-4">Take back control of your time and read only on your desktop, don't let news follow you on your phone.</p>
      </div>
      <div class="w-1/3 px-4 py-8">
        <h3 class="font-bold mt-4">Distraction-Free</h3>
        <p class="font-thin mt-4">No ads. No suggested links. No clickbaits. You decide what content to follow and when to check for updates.</p>
      </div>
      <div class="w-1/3 px-4 py-8">
        <h3 class="font-bold mt-4">Respect News Sources</h3>
        <p class="font-thin mt-4">Read articles in their original format and website. We don't want to steal traffic with in-app readers.</p>
      </div>
      <div class="w-1/3 px-4 py-8">
        <h3 class="font-bold mt-4">Improve Productivity</h3>
        <p class="font-thin mt-4">Spend less time wandering around. Read updates you care about and then get back to work.</p>
      </div>
      <div class="w-1/3 px-4 py-8">
        <h3 class="font-bold mt-4">Read Later</h3>
        <p class="font-thin mt-4">Can't read something right now? Use monocle browser extension to save content for later.</p>
      </div>
      <div class="w-1/3 px-4 py-8">
        <h3 class="font-bold mt-4">Support Micropreneurs</h3>
        <p class="font-thin mt-4">Monocle was created and is maintained by a single developer whose goal is sustainability, not growth.</p>
      </div>
    </section>
    <section class="flex flex-col justify-center items-center text-center mt-16">
      <p><span class="font-bold highlight">Stay up-to-date</span> with blogs, newspapers, <br />YouTube channels, and anything with a feed</p>
      <button class="mt-4 w-56 tracking-widest py-1 text-xl rounded uppercase bg-gray-900 text-gray-100 border-gray-900">Start</button>
      <small class="text-xs text-gray-500"><b>$49</b> one-time payment</small>
    </section>
    </div>
    <footer class="bg-gray-800 mt-16">
    <div class="flex flex-row justify-between items-center container mx-auto text-gray-500 py-8">
      <div class="flex flex-col">
        <h1 class="font-title text-3xl leading-none">Monocle</h1>
        <small>by <a href="https://jordan-pagkalinawan.vercel.app" target="_blank" class="font-bold">Jordan Pagkalinawan</a></small>
      </div>
      <ul class="text- text-sm">
        <li>Contact</li>
        <li>Privacy Policy</li>
        <li>Terms of Service</li>
      </ul>
      </div>
    </footer>
</template>

<script>

export default {
  name: 'App'
};
</script>

<style>
  .highlight {
    position: relative;
  }
  .highlight:after {
    content: '';
    position: absolute;
    top: 2px;
    left: 0;
    top: 0;
    width: full;
    background-color: #742a2a;
    opacity: 0.1;
    width: 100%;
    height: 90%;
    transform: skewX(-10deg);
  }
</style>

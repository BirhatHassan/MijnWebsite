<script setup lang="ts">
</script>

<template>
  <footer class="bg-[#27568B] h-10 mt-30">

    <!-- Bottom row -->
    <section class="flex flex-row justify-between bg-[#27568B] ">
      <div class="flex flex-row">
        <!-- Left column -->
        <div id="footerList">
          <p class="text-white">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 640">
              <path fill="#ffffff" d="M471.1 297.4C483.6 309.9 483.6 330.2
              471.1 342.7L279.1 534.7C266.6 547.2 246.3 547.2 233.8 534.7
              C221.3 522.2 221.3 501.9 233.8 489.4L403.2 320L233.9 150.6
              C221.4 138.1 221.4 117.8 233.9 105.3C246.4 92.8 266.7 92.8
              279.2 105.3L471.2 297.3z"/>
            </svg>
            Over deze website
          </p>

          <p class="text-white">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 640">
              <path fill="#ffffff" d="M471.1 297.4C483.6 309.9 483.6 330.2
              471.1 342.7L279.1 534.7C266.6 547.2 246.3 547.2 233.8 534.7
              C221.3 522.2 221.3 501.9 233.8 489.4L403.2 320L233.9 150.6
              C221.4 138.1 221.4 117.8 233.9 105.3C246.4 92.8 266.7 92.8
              279.2 105.3L471.2 297.3z"/>
            </svg>
            Contact ons
          </p>

          <p class="text-white">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 640">
              <path fill="#ffffff" d="M471.1 297.4C483.6 309.9 483.6 330.2
              471.1 342.7L279.1 534.7C266.6 547.2 246.3 547.2 233.8 534.7
              C221.3 522.2 221.3 501.9 233.8 489.4L403.2 320L233.9 150.6
              C221.4 138.1 221.4 117.8 233.9 105.3C246.4 92.8 266.7 92.8
              279.2 105.3L471.2 297.3z"/>
            </svg>
            Partners
          </p>

          <p class="text-white">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 640">
              <path fill="#ffffff" d="M471.1 297.4C483.6 309.9 483.6 330.2
              471.1 342.7L279.1 534.7C266.6 547.2 246.3 547.2 233.8 534.7
              C221.3 522.2 221.3 501.9 233.8 489.4L403.2 320L233.9 150.6
              C221.4 138.1 221.4 117.8 233.9 105.3C246.4 92.8 266.7 92.8
              279.2 105.3L471.2 297.3z"/>
            </svg>
            Help
          </p>
        </div>

        <!-- Right column -->
        <div id="footerList" class="mr-20">
          <p class="text-white">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 640">
              <path fill="#ffffff" d="M471.1 297.4C483.6 309.9 483.6 330.2
              471.1 342.7L279.1 534.7C266.6 547.2 246.3 547.2 233.8 534.7
              C221.3 522.2 221.3 501.9 233.8 489.4L403.2 320L233.9 150.6
              C221.4 138.1 221.4 117.8 233.9 105.3C246.4 92.8 266.7 92.8
              279.2 105.3L471.2 297.3z"/>
            </svg>
            Toegankelijkheid
          </p>

          <p class="text-white">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 640">
              <path fill="#ffffff" d="M471.1 297.4C483.6 309.9 483.6 330.2
              471.1 342.7L279.1 534.7C266.6 547.2 246.3 547.2 233.8 534.7
              C221.3 522.2 221.3 501.9 233.8 489.4L403.2 320L233.9 150.6
              C221.4 138.1 221.4 117.8 233.9 105.3C246.4 92.8 266.7 92.8
              279.2 105.3L471.2 297.3z"/>
            </svg>
            Cookies & privacy
          </p>

          <p class="text-white">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 640">
              <path fill="#ffffff" d="M471.1 297.4C483.6 309.9 483.6 330.2
              471.1 342.7L279.1 534.7C266.6 547.2 246.3 547.2 233.8 534.7
              C221.3 522.2 221.3 501.9 233.8 489.4L403.2 320L233.9 150.6
              C221.4 138.1 221.4 117.8 233.9 105.3C246.4 92.8 266.7 92.8
              279.2 105.3L471.2 297.3z"/>
            </svg>
            Vacatures
          </p>
        </div>
      </div>
      <div class="pr-20"></div>
    </section>
  </footer>
</template>

<style scoped>
@import "tailwindcss";

#footerList {
  font-weight: 100;
  font-size: 1.3rem;
  display: flex;
  flex-direction: column;
  padding: 1rem;
}

#footerList svg {
  height: 1.1em;
  margin-right: 0.5rem;
  flex-shrink: 0;
}

#footerList p {
  display: flex;
  align-items: center;
  padding-bottom: 0.5rem;
}

#footerList p:hover {
  transition: all 0.3s;
  opacity: 0.8;
  cursor: pointer;
}
</style>


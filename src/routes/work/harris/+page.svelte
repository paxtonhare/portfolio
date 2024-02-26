<script lang="ts">
  import { Avatar } from "flowbite-svelte";
  import { base } from "$app/paths";
</script>

<section class="relative">
  <div class="flex flex-col gap-8 justify-center items-center my-8">
    <div class="w-32 logo">
      <svg viewBox="0 0 195.83 53.5"><title>header-logo</title><path d="M0,0" transform="translate(0.31 -0.14)" style="fill: none;"></path><path d="M59.46,43.5h-5.7v4.08h4.86v1.06H53.76v4.89H52.57V42.44h6.89Z" transform="translate(0.31 -0.14)" fill="currentColor"></path><path d="M68.93,53.53H67.67L66.78,51H61.94l-.89,2.5H59.78l4.09-11.09h1ZM62.29,50h4.13l-2-5.88Z" transform="translate(0.31 -0.14)" fill="currentColor"></path><path d="M77.32,43.56l-.76.76a3.45,3.45,0,0,0-2.59-1c-1.5,0-2.35.82-2.35,2.07a1.59,1.59,0,0,0,.5,1.29,2.9,2.9,0,0,0,1.44.58l1.3.2a3.38,3.38,0,0,1,2,.8,2.79,2.79,0,0,1,.93,2.18c0,2-1.51,3.15-3.83,3.15a4.8,4.8,0,0,1-3.79-1.47l.8-.79a3.79,3.79,0,0,0,3,1.2c1.64,0,2.63-.75,2.63-2.06a1.77,1.77,0,0,0-.54-1.39,2.38,2.38,0,0,0-1.45-.54l-1.29-.19a3.86,3.86,0,0,1-2-.84,2.65,2.65,0,0,1-.86-2.09c0-1.89,1.36-3.12,3.55-3.12A4.54,4.54,0,0,1,77.32,43.56Z" transform="translate(0.31 -0.14)" fill="currentColor"></path><path d="M86.64,43.5H83.43v10H82.24v-10H79V42.44h7.61Z" transform="translate(0.31 -0.14)" fill="currentColor"></path><path d="M88.46,53.53H87V52.07h1.47Z" transform="translate(0.31 -0.14)" fill="currentColor"></path><path d="M102.54,43.5H96.83v4.08h4.86v1.06H96.83v4.89H95.64V42.44h6.9Z" transform="translate(0.31 -0.14)" fill="currentColor"></path><path d="M110.69,43.44c1,1,1.12,2,1.12,4.55s-.08,3.5-1.12,4.55a4.05,4.05,0,0,1-5.53,0c-1-1-1.11-2-1.11-4.55s.06-3.51,1.11-4.55a4,4,0,0,1,5.53,0Zm-4.68.74c-.7.72-.78,1.53-.78,3.81s.08,3.08.78,3.8a2.75,2.75,0,0,0,3.84,0c.7-.72.78-1.53.78-3.8s-.08-3.09-.78-3.81a2.75,2.75,0,0,0-3.84,0Z" transform="translate(0.31 -0.14)" fill="currentColor"></path><path d="M118.85,42.44a3,3,0,0,1,3.28,3.08,2.88,2.88,0,0,1-2.41,3l2.63,5H121l-2.53-4.92h-2.66v4.92h-1.19V42.44Zm-3.07,1.06v4.06h3a2,2,0,1,0,0-4.06Z" transform="translate(0.31 -0.14)" fill="currentColor"></path><path d="M134.16,53.53h-1.1l-2.47-8.88-2.46,8.88H127l-2.84-11.09h1.26l2.17,8.94,2.45-8.94h1.05l2.45,8.94,2.17-8.94H137Z" transform="translate(0.31 -0.14)" fill="currentColor"></path><path d="M146.78,53.53h-1.26l-.89-2.5h-4.85l-.88,2.5h-1.27l4.09-11.09h1l4.07,11.09ZM140.14,50h4.13l-2.05-5.88Z" transform="translate(0.31 -0.14)" fill="currentColor"></path><path d="M153.55,42.54a3,3,0,0,1,3.29,3.08,2.88,2.88,0,0,1-2.42,3l2.64,5h-1.39l-2.52-4.92h-2.67v4.92H149.3V42.54Zm-3.07,1.06v4.06h3a2,2,0,1,0,0-4.06Z" transform="translate(0.31 -0.14)" fill="currentColor"></path><path d="M163.55,42.44a3.69,3.69,0,0,1,2.92,1.17c1,1.06,1,2.68,1,4.38s0,3.31-1,4.37a3.66,3.66,0,0,1-2.92,1.17h-3.8V42.44Zm-2.62,1.06v9h2.42a2.76,2.76,0,0,0,2.18-.82c.72-.76.73-2.13.73-3.67s0-2.92-.73-3.68a2.75,2.75,0,0,0-2.18-.81Z" transform="translate(0.31 -0.14)" fill="currentColor"></path><path d="M170.88,53.53h-1.46V52.07h1.46Z" transform="translate(0.31 -0.14)" fill="currentColor"></path><path d="M27.28,42.62H14.57a.73.73,0,0,1-.4-.13L3.89,34.86a.67.67,0,0,1-.24-.34L-.28,22.06a.78.78,0,0,1,0-.4L3.64,8.25a.73.73,0,0,1,.26-.36L14.4.27a.66.66,0,0,1,.4-.13H27.06a.61.61,0,0,1,.39.13L38,7.9a.6.6,0,0,1,.25.35l3.93,13.41a.68.68,0,0,1,0,.4L38.21,34.52a.73.73,0,0,1-.24.34L27.68,42.49a.68.68,0,0,1-.4.13M15.1,41.27H25.64a117.4,117.4,0,0,0-12.56-10.7,94.46,94.46,0,0,0,2,10.7m-1.54-12A116.79,116.79,0,0,1,26.85,40.58,111.17,111.17,0,0,0,28.7,24.32a73.7,73.7,0,0,0-15.14,4.93M30,24.9a114.42,114.42,0,0,1-1.77,15.49l8.45-6.27A33.1,33.1,0,0,0,30,24.9M5.37,34.28l8.11,6a94.77,94.77,0,0,1-1.81-10.12,34.83,34.83,0,0,0-6.3,4.1M1.5,23.22l3.13,9.93A35.77,35.77,0,0,1,11,29,101.33,101.33,0,0,0,1.5,23.22m29.37.66a33.43,33.43,0,0,1,6.55,8.68l3.14-10a83.57,83.57,0,0,0-9.69,1.29M12.68,15.22a72.51,72.51,0,0,0,.13,12.91,73.86,73.86,0,0,1,15.12-5,47.51,47.51,0,0,0-10.29-5.61c-1.62-.71-3.29-1.45-5-2.29M1.51,21.7a103.13,103.13,0,0,1,9.91,6,74.33,74.33,0,0,1-.09-12.47A39,39,0,0,0,1.51,21.7M29.56,10.92a89.09,89.09,0,0,1,.54,11.74,86.59,86.59,0,0,1,10.06-1.39,66.15,66.15,0,0,0-10.6-10.35M13.7,14.22c1.42.7,2.82,1.33,4.48,2.06a48.62,48.62,0,0,1,10.58,5.81,87.51,87.51,0,0,0-.65-11.89,68.89,68.89,0,0,0-14.41,4M4.62,9.7,1.68,19.76a41.21,41.21,0,0,1,9-5.66,32.22,32.22,0,0,1-6-4.4m25.74.15a65.81,65.81,0,0,1,9.57,9.06L37.07,9.14c-2.21.15-4.47.38-6.71.71M15.2,1.8a66.42,66.42,0,0,0-2.31,11.3A68.88,68.88,0,0,1,27,9,110.73,110.73,0,0,0,15.2,1.8M5.33,8.51a30.56,30.56,0,0,0,6.21,4.56A67.12,67.12,0,0,1,13.59,2.52Zm22.79-6.1c.46,2.06.84,4.15,1.14,6.24,2.12-.33,4.27-.58,6.41-.75ZM17.44,1.48A108,108,0,0,1,27.79,7.93C27.46,5.76,27,3.6,26.52,1.48Z" transform="translate(0.31 -0.14)" style="fill: rgb(240, 0, 10);"></path><path d="M109.87,10.94l-7.6,20.88h4.25l1.27-3.69h7.42l1.23,3.69h4.26l-7.63-20.88Zm-.94,13.75,2.64-7.59,2.55,7.59Zm30.19-7.36c0-3.49-2.52-6.39-6.77-6.39h-8.19V31.83h4.08V23.49h2.94l4.07,8.34H140l-4.67-9A5.62,5.62,0,0,0,139.12,17.33Zm-7,2.76h-3.85V14.57h3.85a2.77,2.77,0,1,1,0,5.52Zm26.7-2.76c0-3.49-2.53-6.39-6.78-6.39h-8.19V31.83h4.09V23.49h2.93l4.07,8.34h4.73l-4.66-9A5.64,5.64,0,0,0,158.79,17.33Zm-7,2.76h-3.83V14.57h3.83a2.77,2.77,0,1,1,0,5.52Zm11.75-9.15h4.07V31.83h-4.07ZM185,21.23a5.87,5.87,0,0,1,1.61,4.43c0,4.05-3.37,6.34-7.75,6.34-3.16,0-5.57-.67-7.62-2.76l2.64-2.64a6.83,6.83,0,0,0,5,1.76c2.41,0,3.7-.91,3.7-2.58a2.32,2.32,0,0,0-.65-1.76,3.11,3.11,0,0,0-1.85-.74l-2.52-.35a7.12,7.12,0,0,1-4.05-1.73,5.54,5.54,0,0,1-1.5-4.1c0-3.73,2.77-6.34,7.28-6.34A8.92,8.92,0,0,1,186,13.2l-2.58,2.55a5.83,5.83,0,0,0-4.28-1.44c-2.18,0-3.23,1.2-3.23,2.64a2,2,0,0,0,.62,1.49,3.53,3.53,0,0,0,1.93.83l2.47.35a6.94,6.94,0,0,1,4,1.61ZM79.25,25.78c0,4.16-3,6.22-6.63,6.22-3,0-5.8-1.37-6.5-4.64l3.65-1.52a2.83,2.83,0,0,0,5.66-.18,2.68,2.68,0,0,0-2.93-2.87h-.15V19.47h.15a2.39,2.39,0,0,0,2.64-2.61A2.57,2.57,0,1,0,70,16.71l-3.61-1.5a6,6,0,0,1,6.19-4.45c3.7,0,6.37,2.46,6.37,6A4.47,4.47,0,0,1,76.55,21a5,5,0,0,1,2.7,4.75ZM94.72,10.93H98.8v20.9H94.72V23.08H87.65v8.75H83.58V10.93h4.07v8.54h7.07ZM56.92,28.19h6.55v3.64H52.85V10.93h4.07Z" transform="translate(0.31 -0.14)" fill="currentColor"></path><path d="M195.51,12.35a3.1,3.1,0,0,1-3.17,3.13,3.12,3.12,0,1,1,3.17-3.13Zm-5.58,0a2.43,2.43,0,0,0,2.43,2.49,2.39,2.39,0,0,0,2.38-2.49,2.4,2.4,0,0,0-2.4-2.47A2.42,2.42,0,0,0,189.93,12.35Zm1.2,1.63V10.87a5.82,5.82,0,0,1,1.2-.11,1.8,1.8,0,0,1,1.08.24.88.88,0,0,1,.3.69.81.81,0,0,1-.64.72v0c.3.09.47.34.57.78a2.41,2.41,0,0,0,.22.75h-.78a2.08,2.08,0,0,1-.24-.75c-.06-.35-.25-.5-.65-.5h-.34V14Zm.74-1.76h.34c.38,0,.72-.15.72-.46s-.21-.47-.66-.47a1.68,1.68,0,0,0-.4,0Z" transform="translate(0.31 -0.14)" fill="currentColor"></path></svg>
    </div>
    <div class="font-light text-gray-500 sm:text-lg dark:text-gray-400">
      <h2 class="mb text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white">Government and Defense Contractor</h2>
    </div>
  </div>
</section>

<section class="relative">
  <div class="py-8 px-4 mx-auto max-w-screen-md">
    <div class="max-w-screen-lg text-gray-500 sm:text-lg dark:text-gray-400">
      <h2 class="mb-4 text-4xl tracking-tight font-bold text-gray-900 dark:text-white">Congratulations!</h2>
      <p>
        You've traveled back in time to the dark ages (a.k.a. the beginning of my career). I started Harris in 2000 right out of college.
      </p>
    </div>
  </div>
</section>

<section class="relative">
  <div class="py-8 px-4 mx-auto max-w-screen-md">
    <div class="max-w-screen-lg text-gray-500 sm:text-lg dark:text-gray-400">
    <h2 class="mb-4 text-4xl tracking-tight font-bold text-gray-900 dark:text-white">Stat Scanner</h2>
    <div class="flex items-center justify-center">
      <Avatar src="{base}/statscanner.gif" alt="Stat Logo" size="lg"/>
    </div>
    <p class="mb-4">
      Shortly after joining Harris I was randomly assigned to an R&D project. This rag tag group of engineers had created a vulnerability
      assessment tool for Windows computers. It ran remotely against Windows computers on a network and reported back with a list of vulnerabilities
      found. It was able to automatically remediate most of them. I quickly became one of the leads on the project learned to be a full stack developer.
    </p>
    <p class="mb-4">
      As the product began to make inroads within the intelligence community Harris decided to run the group like a startup. We were given a budget
      and hired a sales team. I was turned into a sales engineer and began to travel the country with the sales team. I was responsible for the technical
      part of the sale. I would present the product to the customer and answer any technical questions they had. I would also help the customer understand
      how to use the product. I ran training classes for our customers.
    </p>
    <p class="mb-4">
      During this time I traveled to nearly every Army base in the United States.
    </p>
    <p class="mb-4">
      <b>Fun Fact:</b> I was in Fort Huachuca Arizona on 9/11. I was there to train the Army on how to use our product. The morning of 9/11 I came into the
      hotel lobby for breakfast only to see the first tower fall on the TV. I was going to be stuck in Arizona for a week as all flights were grounded, but my
      boss and I rented a car and drove all the way back to Melbourne Florida.
    </p>
  </div>
</section>

<section class="relative">
  <div class="py-8 px-4 mx-auto max-w-screen-md">
    <div class="max-w-screen-lg text-gray-500 sm:text-lg dark:text-gray-400">
    <h2 class="mb-4 text-4xl tracking-tight font-bold text-gray-900 dark:text-white">Secnet 11</h2>
    <div class="flex items-center justify-center">
      <Avatar src="{base}/secnet.jpg" alt="Secnet Logo" size="lg"/>
    </div>
    <p class="mb-4">
      I briefly left Harris to join a doomed startup. After the startup failed I contacted my old team from Harris and they hired me back. They had
      moved on to another division of Harris and were working on the Secnet 11 product. This was a network security product that was designed to
      encrypt data on the network. It was basically wifi for top secret communications.
    </p>
    <p class="mb-4">
      Because of my ridiculous ability to pick up new things, my former colleagues were eager to have me join them again. During the interview process
      I had to speak with an engineering manager from the division. He told me to my face that I was going to fail in the role due to my lack of experience
      working on embedded hardware. He went as far as to say he was going to revel in my failure. I was hired and within a month I was the lead developer on the project.
    </p>

    <h3 class="my-4 text-xl tracking-tight font-bold text-gray-900 dark:text-white">My Role</h3>
    <p class="mb-4">
      I was the lead for the new e-mod. Currently there was r-mod (Radio Module) which provided wifi. I was to create the e-mod (Ethernet Module) which
      would provide a wired connection to the network. I was responsible for the software design of the e-mod. I wrote the software in C and C++ with a smattering
      of assembly language. I worked closely with the hardware team to ensure that the software and hardware worked together. There's nothing quite like
      debugging TCP traffic with an oscilloscope.
    </p>
  </div>
</section>

<style>
  .dark .logo svg {
    color: #fff;
  }
</style>

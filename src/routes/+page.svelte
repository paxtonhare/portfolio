<script lang="ts">
  import { Portfolio, PortfolioItem } from "flowbite-svelte-blocks";
  import { Avatar } from "flowbite-svelte";
  import { LinkedinSolid, GithubSolid, YoutubeSolid } from 'flowbite-svelte-icons';

  const linkTitle = 'View Details';

  const portfolios = [
    {
      customer: "Bestomer Inc.",
      title: "Revolutionizing CRM",
      description: "Hired as employee 10 to help realize Bestomer's vision.",
      href: "/work/bestomer",
      linkTitle
    },
    {
      customer: "Wave Fitness",
      title: "Swimming Fitness Machine",
      description: "Created the UI for the Wave swimming machine.",
      href: "/work/wave",
      linkTitle
    },
    {
      customer: "Confluent Inc.",
      title: "Making Kafka 10x Better",
      description: "Hired to develop Accelerators for the Customer Innovation team.",
      href: "/work/confluent",
      linkTitle
    },
    {
      customer: "Hare Squared, LLC",
      title: "My Side Hustle App Development Company",
      description: "One of my apps was in the top ten in the App Store.",
      href: "/work/haresquared",
      linkTitle
    },
    {
      customer: "MarkLogic",
      title: "The Single Platform that Unlocks Data Agility",
      description: "Created the flagship product Data Hub Framework.",
      href: "/work/marklogic",
      linkTitle
    },
    {
      customer: "L3 Harris",
      title: "Government and Defense Contractor",
      description: "A long time ago... Created some cool stuff here.",
      href: "/work/harris",
      linkTitle
    }
  ];
</script>

<section class="relative">
  <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16 lg:px-6">
    <div class="flex flex-col items-center justify-center">
      <Avatar src="https://gravatar.com/avatar/1f479fddb8ac77c0258759f2a8014b875910fed0fe318e55e92360cb49ca2f8d?size=256" alt="Paxton" size="xl"/>
      <h1 class="text-4xl font-bold text-gray-900 dark:text-white">Hi, I'm Paxton</h1>
      <h3 class="mt-8 text-2xl font-light text-gray-500 dark:text-gray-400">Socials</h3>
      <div class="flex flex-col items-center border-2 rounded-lg p-4 min-w-64">
        <div class="flex items-center gap-8">
          <a href="https://www.linkedin.com/in/paxtonhare/" class="flex justify-center items-center">
            <LinkedinSolid class="dark:text-gray-100" size="xl" />
          </a>
          <a href="https://www.github.com/paxtonhare" class="flex justify-center items-center">
            <GithubSolid class="dark:text-gray-100" size="xl"/>
          </a>
          <a href="https://www.youtube.com/@paxtonhare" class="flex justify-center items-center">
            <YoutubeSolid class="dark:text-gray-100" size="xl"/>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="relative">
  <div class="max-w-screen-xl px-4 py-8 mx-auto lg:px-6 sm:py-8 lg:py-8">
    <Portfolio title="My work" subtitle="Spanning 20+ years of software development.">
      {#each portfolios as item}
        <PortfolioItem {item} />
      {/each}
    </Portfolio>
  </div>
</section>

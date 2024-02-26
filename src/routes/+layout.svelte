<script>
	import '../app.pcss';
	import { Avatar, DarkMode } from 'flowbite-svelte';
  import { Navbar, NavBrand } from 'flowbite-svelte';
  import { base } from '$app/paths';

  let navClass = 'bg-white border-gray-200 px-4 lg:px-6 py-2.5 dark:bg-gray-800';
  let navDivClass = 'flex flex-wrap justify-between items-center mx-auto max-w-screen-xl';
	let darkmodebtn =
		'text-gray-500 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 focus:outline-none focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 rounded-lg text-lg p-2.5 fixed right-4 top-2 z-50';
  const year = new Date().getFullYear();
</script>

<header>
  <Navbar let:hidden let:toggle fluid={false} {navClass} {navDivClass}>
    <NavBrand href="{base}">
      <Avatar src="https://gravatar.com/avatar/1f479fddb8ac77c0258759f2a8014b875910fed0fe318e55e92360cb49ca2f8d?size=256" alt="Paxton" size="sm" class="mr-4" />
      <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white"> Paxton's Portfolio </span>
    </NavBrand>
    <div class="flex items-center lg:order-2">
      <DarkMode btnClass={darkmodebtn} />
    </div>
  </Navbar>
</header>
<slot />

<section class="relative flex items-center justify-center mt-8">
  <span class="text-sm text-gray-500 sm:text-center dark:text-gray-400">© {year} Paxton Hare. All Rights Reserved.</span>
</section>
H

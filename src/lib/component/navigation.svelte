<script lang="ts">
    import { page } from '$app/stores';
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
    let activeUrl: string;
    $: activeUrl = $page.url.pathname;
import Mode from '$lib/component/mode.svelte';

import { DarkMode } from 'flowbite-svelte';
  
  let btnClass = ' text-gray-500 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 rounded-lg text-xl p-2';
  let activeClass = "text-light-100";
  let nonActiveClass = "text-white";
  </script>


<Navbar let:hidden let:toggle class="bg-dark-100 dark:bg-dark-100 flex w-full">
    <div class=" flex flex-wrap justify-between  md:justify-between  gap-5  items-center w-full md:w-4/6">
    <NavBrand href="/" class="">
      <img src="src/lib/images/logo.png" class="  h-10 sm:h-9 " alt="Flowbite Logo" />
      
  
    </NavBrand>
    <NavHamburger on:click={toggle}/>
    <NavUl {hidden} {activeClass} {nonActiveClass} {activeUrl} ulClass="flex flex-col md:flex-row-reverse gap-5 h-60 md:h-auto w-full   bg-dark-100 dark:bg-dark-100 border-0 text-center" >

      <NavLi id="list" href="/">گشتی</NavLi>
      <NavLi id="list" href="/category">بەرهەمەکان</NavLi>
      <NavLi id="list" href="/about">دەربارەی ئێمە</NavLi>

      <DarkMode {btnClass} class="flex justify-center"/>

    </NavUl>


<Mode />

</div>
  </Navbar>
  


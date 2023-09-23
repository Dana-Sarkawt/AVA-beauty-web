<script>
// @ts-nocheck
import {fade,fly} from "svelte/transition";
    import { Card, Button, Rating, Badge } from 'flowbite-svelte';
  </script>
  

  <div class="flex w-full container mx-auto h-full mt-5 gap-3 flex-wrap	justify-center" in:fly = {{y:100, duration: 1200}} dir="rtl">
  <Card padding="none" class="w-48 h-full" >
    <a href="/" class="bg-gray-100	dark:bg-dark-100">
      <img class="p-8 rounded-t-lg" src="src/lib/images/s-1.png" alt="product 1" />
    </a>
    <div class="px-5 pb-5 bg-gray-100 dark:bg-dark-100">
      <a href="/">
        <p class="text-lg  tracking-tight text-gray-900 dark:text-white">سابوونی هەنگوین</p>
      </a>
      <Rating rating="4" size="24" class="mt-2.5 mb-5">
        <Badge slot="text" class="ml-3 text-gray-600 dark:bg-light-100 dark:text-dark-200">4</Badge>
      </Rating>
      <div class="flex justify-between items-center">
        <span class="text-3xl font-bold text-gray-900 dark:text-white">$5</span>
        <Button href="/" class="bg-dark-100 hover:bg-light-100 hover:text-dark-100 dark:bg-white dark:text-dark-200 dark:hover:bg-light-100 dark:hover:text-white">داواکردن</Button>
      </div>
    </div>
  </Card>
  




  <Card padding="none" class="w-48 h-full">
    <a href="/" class="bg-gray-100	dark:bg-dark-100">
      <img class="p-8 rounded-t-lg" src="src/lib/images/s-1.png" alt="product 1" />
    </a>
    <div class="px-5 pb-5 bg-gray-100 dark:bg-dark-100">
      <a href="/">
        <h5 class="text-md font-semibold tracking-tight text-gray-900 dark:text-white">سابوونی هەنگوین</h5>
      </a>
      <Rating rating="4" size="24" class="mt-2.5 mb-5">
        <Badge slot="text" class="ml-3 text-gray-600 dark:bg-light-100 dark:text-dark-200">4</Badge>
      </Rating>
      <div class="flex justify-between items-center">
        <span class="text-3xl font-bold text-gray-900 dark:text-white">$5</span>
        <Button href="/" class="bg-dark-100 hover:bg-light-100 hover:text-dark-100 dark:bg-white dark:text-dark-200 dark:hover:bg-light-100 dark:hover:text-white">داواکردن</Button>
      </div>
    </div>
  </Card>






  <Card padding="none" class="w-48 h-full">
    <a href="/" class="bg-gray-100	dark:bg-dark-100">
      <img class="p-8 rounded-t-lg" src="src/lib/images/s-1.png" alt="product 1" />
    </a>
    <div class="px-5 pb-5 bg-gray-100 dark:bg-dark-100">
      <a href="/">
        <h5 class="text-md font-semibold tracking-tight text-gray-900 dark:text-white">سابوونی هەنگوین</h5>
      </a>
      <Rating rating="4" size="24" class="mt-2.5 mb-5">
        <Badge slot="text" class="ml-3 text-gray-600 dark:bg-light-100 dark:text-dark-200">4</Badge>
      </Rating>
      <div class="flex justify-between items-center">
        <span class="text-3xl font-bold text-gray-900 dark:text-white">$5</span>
        <Button href="/" class="bg-dark-100 hover:bg-light-100 hover:text-dark-100 dark:bg-white dark:text-dark-200 dark:hover:bg-light-100 dark:hover:text-white">داواکردن</Button>
      </div>
    </div>
  </Card>

</div>
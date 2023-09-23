<script>
    import { Card, Button, Rating, Badge } from 'flowbite-svelte';
    import {fade,fly} from "svelte/transition";

  </script>
  <div class="mx-auto container w-full h-auto flex justify-center" in:fly = {{y:100, duration: 1200}}>
  <Card padding="none" class="w-60 h-80 flex mx-auto container mt-5" >
    <a href="/">
      <img class="p-8 rounded-t-lg" src="src/lib/images/s-1.png" alt="product 1" />
    </a>
    <div class="px-5 pb-5">
      <a href="/">
        <h5 class="text-xl text-center font-semibold tracking-tight text-gray-900 dark:text-white">سابوون</h5>
      </a>
   
      <div class="flex justify-between items-center">
   
      </div>
    </div>
  </Card>
</div>
  <style>
    h5{
        font-size: 32px;
    }
  </style>
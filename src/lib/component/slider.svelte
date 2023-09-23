<script>
    import { Carousel, CarouselTransition } from 'flowbite-svelte';
    // ./imageData/+server.js has the following
    export const images = [
      {
        id: 0,
        name: 'سابوونی سرووشتی ئیڤا',
        imgurl: 'src/lib/images/b-1.jpg',
        
      },
      {
        id: 1,
        name: 'سابوونی سرووشتی ئیڤا',
        imgurl: 'src/lib/images/b-2.jpg',
        
      },
    
      {
        id: 2,
        name: 'سابوونی سرووشتی ئیڤا',
        imgurl: 'src/lib/images/b-3.jpg',
    
      }
    
    ];

    
  </script>




<div class="w-full h-full ">
  <script>
    import { Carousel } from 'flowbite-svelte';
    import { images } from './imageData/+server.js';
  </script>
  
  <div  class="container  mx-auto dark p-2 ">
    <Carousel {images}
    showCaptions={true}
    classSlide=" flex items-center justify-center h-full w-full !rounded-none !bg-transparent"
    classDiv="w-full  sm:!h-[400px] !rounded-none !bg-transparent"
    imgFit="cover"
    classImg="!bg-none !rounded-md animate-[fadeIn_.5s_ease-in-out_1] h-full "
    classThumb="p-0 rounded-md shadow-xl h-24 w-24 hover:outline hover:outline-light-100"
    classThumbDiv="bg-transparent"
    thumbBtnClass="m-1"
  captionClass="bg-dark-100 text-center py-4"
    
    />
  </div>
</div>







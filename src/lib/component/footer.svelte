<script>
    import { Footer, FooterCopyright, FooterLinkGroup, FooterBrand, FooterLink } from 'flowbite-svelte';
  </script>
    <div class="w-full h-auto bg-dark-200"> 
  <Footer footerType="logo" class="text-center mt-72 bg-dark-100 dark:bg-dark-100	w-full">
    <div class="flex items-center justify-center justify-between w-full">
      <img src="src/lib/images/logo.png" class="text-center h-9 md:h-24 " alt="Flowbite Logo" />
      <FooterLinkGroup  ulClass="flex justify-center flex-wrap items-center mb-6 text-sm text-gray-500 sm:mb-0 dark:text-gray-400">
        <FooterLink href="/">بەرهەمەکان</FooterLink>
        <FooterLink href="/">دەربارەی ئێمە</FooterLink>
        
      </FooterLinkGroup>
    </div>
    <hr class="my-6 border-gray-200 sm:mx-auto dark:border-gray-700 lg:my-8" />
    <FooterCopyright href="/" by="Eva Beauty" />
    <h4 class="text-gray-300">درووستکردنی وێبسایت: دانا سەرکەوت محمد</h4>
  </Footer>
</div>
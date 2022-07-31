<script>
    import { Splide, SplideSlide } from '@splidejs/svelte-splide';
    import '@splidejs/splide/dist/css/themes/splide-default.min.css';

    let images = `object-contain`
</script>
    
    <Splide class="w-full"  options={ { rewind: true } } aria-label="My Favorite Images">
      <!-- <SplideSlide>
        <div class="h-96 w-full bg-[url('mage1.jpg')] bg-cover bg-no-repeat"></div>
      </SplideSlide>
      <SplideSlide>
        <div class="h-96 w-full bg-[url('mage2.jpg')] bg-cover bg-no-repeat bg-center"></div>
      </SplideSlide>
      <SplideSlide>
        <div class="h-96 w-full bg-[url('mage3.jpg')] bg-cover bg-no-repeat bg-bottom"></div>
      </SplideSlide> -->

      <SplideSlide>
        <div class="h-[480px] w-full bg-teal-500"></div>
      </SplideSlide>
      <SplideSlide>
        <div class="h-[480px] w-full bg-orange-500"></div>
      </SplideSlide>
      <SplideSlide>
        <div class="h-[480px] w-full bg-pink-500"></div>
      </SplideSlide>

    </Splide>
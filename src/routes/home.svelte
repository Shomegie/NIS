<script>
    import { Splide, SplideSlide } from '@splidejs/svelte-splide';
    import '@splidejs/splide/dist/css/themes/splide-default.min.css';

    let images = `object-contain`
</script>

<section>
<!-- carousel start -->
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

<!-- carousel end -->

    <div class="flex w-3/6 mb-4 mt-8 mx-auto bg-stone-100 ">
        <div class="w-1/3 aspect-square bg-stone-200"></div>
    </div>

<!-- Educationl Programs start -->
    <div class="flex justify-center pt-4 w-full">
        <p class="text-xl">Educational Programs</p>
    </div>
    <div class="grid gap-8 py-6 grid-cols-1 md:grid-cols-2 xl:grid-cols-4 w-5/6 mx-auto">
        <div class="rounded-lg bg-blue-500 h-auto aspect-square"></div>
        <div class="rounded-lg bg-pink-500 h-auto aspect-square"></div>
        <div class="rounded-lg bg-blue-500 h-auto aspect-square"></div>
        <div class="rounded-lg bg-pink-500 h-auto aspect-square"></div>
    </div>
<!-- Educationl Programs end -->

    <div class="my-4  h-32 w-5/6 mx-auto bg-amber-300"></div>

    <div class="grid my-8 gap-8 grid-cols-3 w-5/6 mx-auto">
        <div class="bg-stone-200 h-64 w-full"></div>
        <div class="bg-stone-200 h-64 w-full"></div>
        <div class="bg-stone-200 h-64 w-full"></div>

        <div class="bg-stone-200 h-64 w-full"></div>
        <div class="bg-stone-200 h-64 w-full"></div>
        <div class="bg-stone-200 h-64 w-full"></div>
    </div>

    <div class="my-4  h-32 w-5/6 mx-auto bg-amber-300"></div>

</section>

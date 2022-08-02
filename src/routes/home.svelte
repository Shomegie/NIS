<script>
    import { Splide, SplideSlide } from '@splidejs/svelte-splide';
    import '@splidejs/splide/dist/css/themes/splide-default.min.css';

    let images = `object-contain`
    let academics =`h-48 bg-blue-100 flex flex-col relative`
</script>


<section id="carousel">
    <div class="h-[560px] bg-blue-900 w-full relative">
        <Splide class="w-full"  options={ { rewind: true } } aria-label="My Favorite Images">
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
        <div class="absolute flex bottom-8 right-0 px-2 z-50">
            <div class="h-32 w-40 bg-zinc-300"></div>
            <div class="h-32 w-40 bg-stone-600"></div>
            <div class="h-32 w-40 bg-black"></div>
        </div>
    </div>
</section>

<section id="Academics">
    <div class="">
        <div class="flex justify-center pt-8 pb-2 font-bold font-serif text-xl text-zinc-800" >Academics</div>
        <div class="flex justify-center text-center w-2/5 xl:w-1/5 mx-auto" >Architecto eius voluptates incidunt velit laudantium, ptates incidunt veli!</div>
    </div>
    <div class="grid grid-cols-3 gap-8 pt-8 md:w-full md:px-8 xl:w-4/6 mx-auto">
        <div class={academics}>
            <div class="flex py-4 px-6 space-x-1 ">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 stroke-current text-red-500" fill="none"  viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M20 7l-8-4-8 4m16 0l-8 4m8-4v10l-8 4m0-10L4 7m8 4v10M4 7v10l8 4" />
                </svg>
                <p class="font-extrabold text-lg font-serif text-blue-900">Nursery</p>
            </div>
            <div class="px-6 text-xs text-stone-700">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Minima a dolor consectetur odit cum.</div>
            <div class="px-6 absolute bottom-4 font-bold font-serif text-xs text-blue-900 cursor-pointer hover:text-gray-700">Nursery -></div>
        </div>
        <div class={academics} id="primary">
            <div class="flex py-4 px-6 space-x-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7 text-red-500" viewBox="0 0 20 20" fill="currentColor">
                    <path fill-rule="evenodd" d="M10.496 2.132a1 1 0 00-.992 0l-7 4A1 1 0 003 8v7a1 1 0 100 2h14a1 1 0 100-2V8a1 1 0 00.496-1.868l-7-4zM6 9a1 1 0 00-1 1v3a1 1 0 102 0v-3a1 1 0 00-1-1zm3 1a1 1 0 012 0v3a1 1 0 11-2 0v-3zm5-1a1 1 0 00-1 1v3a1 1 0 102 0v-3a1 1 0 00-1-1z" clip-rule="evenodd" />
                  </svg>
                <p class="font-extrabold text-lg font-serif text-blue-900">Primary</p>
            </div>
            <div class="px-6 text-xs text-stone-700">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Minima a dolor consectetur odit cum.</div>
            <div class="px-6 absolute bottom-4 font-bold font-serif text-xs text-blue-900 cursor-pointer hover:text-gray-700">Primary Education -></div>
        </div>
        <div class={academics}>
            <div class="flex py-4 px-6 space-x-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7 fill-current text-red-500" viewBox="0 0 20 20" >
                    <path d="M10.394 2.08a1 1 0 00-.788 0l-7 3a1 1 0 000 1.84L5.25 8.051a.999.999 0 01.356-.257l4-1.714a1 1 0 11.788 1.838L7.667 9.088l1.94.831a1 1 0 00.787 0l7-3a1 1 0 000-1.838l-7-3zM3.31 9.397L5 10.12v4.102a8.969 8.969 0 00-1.05-.174 1 1 0 01-.89-.89 11.115 11.115 0 01.25-3.762zM9.3 16.573A9.026 9.026 0 007 14.935v-3.957l1.818.78a3 3 0 002.364 0l5.508-2.361a11.026 11.026 0 01.25 3.762 1 1 0 01-.89.89 8.968 8.968 0 00-5.35 2.524 1 1 0 01-1.4 0zM6 18a1 1 0 001-1v-2.065a8.935 8.935 0 00-2-.712V17a1 1 0 001 1z" />
                </svg>
                <p class="font-extrabold text-lg font-serif text-blue-900">Secondary</p>
            </div>
            <div class="px-6 text-xs text-stone-700">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Minima a dolor consectetur odit cum.</div>
            <div class="px-6 absolute bottom-4 font-bold font-serif text-xs text-blue-900 cursor-pointer hover:text-gray-700">Secondary Education -></div>
        </div>        
    </div>
</section>

<section>
    <div class="flex py-10 md:w-full md:px-8 xl:w-4/6 mx-auto ">
        <div class="h-40 w-3/5">
            <div class="pt-4 font-extrabold text-xl text-center font-serif text-blue-900">About NIS</div>
            <div class="text-center text-sm pt-4 text-stone-600">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae hic eveniet qui neque nemo tempore quas accusantium quod impedit architecto! Ducimus ea odio itaque, 
                optio nihil eaque eum magni harum!</div>
        </div>
        <div class="h-40 w-2/5 bg-teal-400"></div>

    </div>
</section>

<section>
    <div class="w-full h-32 bg-stone-100"></div>
</section>

<section class="my-10">
    <div class="h-80  w-full xl:w-5/6  mx-auto grid xl:px-4 gap-6 grid-cols-3 ">
        <div class="h-full bg-teal-400"></div>
        <div class="h-full bg-slate-500"></div>
        <div class="contacts-div h-full bg-slate-50 shadow-md">
            <div class="flex flex-col h-full">
                <div class="h-1/5 px-4 flex items-center font-serif font-bold text-xl text-stone-600 border-b border-slate-100">Contact us</div>
                <div class="h-1/6 border-b flex border-slate-100 px-4 items-center">
                    <div class="text-xs w-1/3 flex items-center text-slate-500 ">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd" />
                          </svg>
                        <p>Address:</p> 
                    </div>
                    <p class="text-xs w-2/3 text-slate-600">Lorem ipsum dolor sit, amet consectetur adipisicing.</p>
                </div>
                <div class="h-1/6 border-b flex border-slate-100 px-4 items-center">
                    <div class="text-xs w-1/3 flex items-center text-slate-500 ">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M12 18h.01M8 21h8a2 2 0 002-2V5a2 2 0 00-2-2H8a2 2 0 00-2 2v14a2 2 0 002 2z" />
                          </svg>
                        <p>Phone:</p> 
                    </div>
                    <p class="text-xs w-2/3 text-slate-600">+234 555 5555</p>
                </div>
                <div class="h-1/6 border-b flex border-slate-100 px-4 items-center">
                    <div class="text-xs w-1/3 flex items-center text-slate-500 space-x-1">
                        <svg xmlns="http://www.w3.org/2000/svg" class="fill-current text-red-700" viewBox="0 0 24 24" width="16" height="16">
                            <path fill="none" d="M0 0h24v24H0z"/><path d="M3 3h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1zm17 4.238l-7.928 7.1L4 7.216V19h16V7.238zM4.511 5l7.55 6.662L19.502 5H4.511z"/>
                        </svg>
                        <p>Email:</p> 
                    </div>
                    <p class="text-xs w-2/3 text-slate-600">sample@gmail.com</p>
                </div>
                <div class="h-1/6 border-b flex border-slate-100 px-4 items-center">
                    <div class="text-xs w-1/3 flex space-x-1 items-center text-slate-500">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="16" height="16" class="fill-current text-blue-600"><path fill="none" d="M0 0h24v24H0z"/>
                            <path d="M15.402 21v-6.966h2.333l.349-2.708h-2.682V9.598c0-.784.218-1.319 1.342-1.319h1.434V5.857a19.19 19.19 0 0 0-2.09-.107c-2.067 0-3.482 1.262-3.482 3.58v1.996h-2.338v2.708h2.338V21H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1h-4.598z"/>
                        </svg>
                        <p>Facebook:</p> 
                    </div>
                    <p class="text-xs w-2/3 text-slate-600">nis.facebook.com</p>
                </div>

            </div>
        </div>

    </div>
</section>


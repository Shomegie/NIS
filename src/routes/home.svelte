<script>
    import { Splide, SplideSlide } from '@splidejs/svelte-splide';
    import '@splidejs/splide/dist/css/themes/splide-default.min.css';

    let images = `object-contain`
    let academics =`h-48 bg-stone-50 flex flex-col relative`
</script>


<section id="carousel">
    <div class="texture">
    <div class="h-[560px] bg-indigo-900 bg-opacity-0 w-full relative">

        <Splide class="w-full"  options={ { rewind: true } } aria-label="My Favorite Images">
            <SplideSlide>
                <div class="h-[480px] w-full bg-teal-500 relative">
                    <img src="/jpg/slide_01.jpg" alt="caro_1" class="object-cover h-full w-full ">
                    <div class="absolute top-0 bg-blue-900 bg-opacity-20 h-full w-full flex">
                        <div class="w-full xl:w-1/2"> 
                            <div class="w-full xl:w-4/5 h-full p-8  bg-white bg-opacity-30 rounded relative rounded-ful">
                                <img class = "image h-44 opacity-80  " src="/png/NIS_6.png" alt="temp logo">
                                <div class="text-yellow-700 b bg-opacity-40">
                                    <div class="bg-white w-fit bg-opacity-70 px-1">Nithalos International School</div> 
                                    <div class="bg-white w-fit bg-opacity-70 px-1">Nursery, Primary & Secondary School</div>
                                    <div class="bg-white w-fit bg-opacity-70 px-1">99 Obiwali Rd, Rumuigbo 500272, Port Harcourt</div>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </SplideSlide>
            <SplideSlide>
                <div class="h-[480px] w-full bg-teal-500 relative">
                    <img src="/jpg/slide_02.jpg" alt="caro_1" class="object-cover h-full w-full ">
                    <div class="absolute top-0 bg-blue-900 bg-opacity-20 h-full w-full flex">
                        <div class="w-full xl:w-1/2"> 
                            <div class="w-full xl:w-4/5 h-full p-8  bg-white bg-opacity-30 rounded relative rounded-ful">
                                <img class = "image h-44 opacity-80  " src="/png/NIS_6.png" alt="temp logo">
                                <div class="text-yellow-700 b bg-opacity-40">
                                    <div class="bg-white w-fit bg-opacity-70 px-1">Nithalos International School</div> 
                                    <div class="bg-white w-fit bg-opacity-70 px-1">Nursery, Primary & Secondary School</div>
                                    <div class="bg-white w-fit bg-opacity-70 px-1">99 Obiwali Rd, Rumuigbo 500272, Port Harcourt</div>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </SplideSlide>
            <SplideSlide>
                <div class="h-[480px] w-full bg-teal-500 relative">
                    <img src="/jpg/slide_03.jpg" alt="caro_1" class="object-cover h-full w-full ">
                    <div class="absolute top-0 bg-blue-900 bg-opacity-20 h-full w-full flex">
                        <div class="w-full xl:w-1/2"> 
                            <div class="w-full xl:w-4/5 h-full p-8  bg-white bg-opacity-30 rounded relative rounded-ful">
                                <img class = "image h-44 opacity-80  " src="/png/NIS_6.png" alt="temp logo">
                                <div class="text-yellow-700 b bg-opacity-40">
                                    <div class="bg-white w-fit bg-opacity-70 px-1">Nithalos International School</div> 
                                    <div class="bg-white w-fit bg-opacity-70 px-1">Nursery, Primary & Secondary School</div>
                                    <div class="bg-white w-fit bg-opacity-70 px-1">99 Obiwali Rd, Rumuigbo 500272, Port Harcourt</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </SplideSlide>
            <SplideSlide>
                <div class="h-[480px] w-full bg-teal-500 relative">
                    <img src="/jpg/slide_04.jpg" alt="caro_1" class="object-cover h-full w-full ">
                    <div class="absolute top-0 bg-blue-900 bg-opacity-20 h-full w-full flex">
                        <div class="w-full xl:w-1/2"> 
                            <div class="w-full xl:w-4/5 h-full p-8  bg-white bg-opacity-30 rounded relative rounded-ful">
                                <img class = "image h-44 opacity-80  " src="/png/NIS_6.png" alt="temp logo">
                                <div class="text-yellow-700 b bg-opacity-40">
                                    <div class="bg-white w-fit bg-opacity-70 px-1">Nithalos International School</div> 
                                    <div class="bg-white w-fit bg-opacity-70 px-1">Nursery, Primary & Secondary School</div>
                                    <div class="bg-white w-fit bg-opacity-70 px-1">99 Obiwali Rd, Rumuigbo 500272, Port Harcourt</div>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </SplideSlide>
            <SplideSlide>
                <div class="h-[480px] w-full bg-teal-500 relative">
                    <img src="/jpg/slide_05.jpg" alt="caro_1" class="object-cover h-full w-full ">
                    <div class="absolute top-0 bg-blue-900 bg-opacity-20 h-full w-full flex">
                        <div class="w-full xl:w-1/2"> 
                            <div class="w-full xl:w-4/5 h-full p-8  bg-white bg-opacity-30 rounded relative rounded-ful">
                                <img class = "image h-44 opacity-80  " src="/png/NIS_6.png" alt="temp logo">
                                <div class="text-yellow-700 b bg-opacity-40">
                                    <div class="bg-white w-fit bg-opacity-70 px-1">Nithalos International School</div> 
                                    <div class="bg-white w-fit bg-opacity-70 px-1">Nursery, Primary & Secondary School</div>
                                    <div class="bg-white w-fit bg-opacity-70 px-1">99 Obiwali Rd, Rumuigbo 500272, Port Harcourt</div>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </SplideSlide>
        </Splide>
        <div class="absolute hidden sm:flex bottom-8 right-0 px-2 z-50">
            <div class="h-32 w-40 bg-zinc-300"></div>
            <div class="h-32 w-40 bg-stone-600"></div>
            <div class="h-32 w-40 bg-black"></div>
        </div>
    </div>
    <div class="flex w-full">
        <div class="h-1 w-1/3 bg-red-500"></div>
        <div class="h-1 w-1/3 bg-green-500"></div>
        <div class="h-1 w-1/3 bg-yellow-300"></div>
    </div>
</div>
</section>

<section id="Academics">
    <div class="">
        <div class="flex justify-center pt-8 pb-2 font-bold font-serif text-xl text-zinc-800" >Academics</div>
        <div class="flex justify-center text-center w-4/5 xl:w-1/5 mx-auto" >Architecto eius voluptates incidunt velit laudantium, ptates incidunt veli!</div>
    </div>
    <div class="grid grid-cols-1 px-14 xl:grid-cols-3 gap-x-8 pt-8 md:w-full md:px-8 md:grid-cols-3 xl:w-4/6 mx-auto">
        <div class={academics} id="nursery">
            <div class="flex py-4 px-6 space-x-1 border-t-4 border-yellow-300">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 stroke-current text-yellow-500" fill="none"  viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M20 7l-8-4-8 4m16 0l-8 4m8-4v10l-8 4m0-10L4 7m8 4v10M4 7v10l8 4" />
                </svg>
                <p class="font-extrabold text-lg font-serif text-blue-900">Nursery</p>
            </div>
            <div class="px-6 text-xs text-stone-700">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Minima a dolor consectetur odit cum.</div>
            <div class="px-6 absolute bottom-4 font-bold font-serif text-xs text-blue-900 cursor-pointer hover:text-gray-700">Nursery -></div>

        </div>
        <div class={academics} id="primary">
            <div class="flex py-4 px-6 space-x-1 border-t-4 border-red-500">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7 text-red-500" viewBox="0 0 20 20" fill="currentColor">
                    <path fill-rule="evenodd" d="M10.496 2.132a1 1 0 00-.992 0l-7 4A1 1 0 003 8v7a1 1 0 100 2h14a1 1 0 100-2V8a1 1 0 00.496-1.868l-7-4zM6 9a1 1 0 00-1 1v3a1 1 0 102 0v-3a1 1 0 00-1-1zm3 1a1 1 0 012 0v3a1 1 0 11-2 0v-3zm5-1a1 1 0 00-1 1v3a1 1 0 102 0v-3a1 1 0 00-1-1z" clip-rule="evenodd" />
                  </svg>
                <p class="font-extrabold text-lg font-serif text-blue-900">Primary</p>
            </div>
            <div class="px-6 text-xs text-stone-700">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Minima a dolor consectetur odit cum.</div>
            <div class="px-6 absolute bottom-4 font-bold font-serif text-xs text-blue-900 cursor-pointer hover:text-gray-700">Primary Education -></div>
        </div>
        <div class={academics}>
            <div class="flex py-4 px-6 space-x-1 border-t-4 border-indigo-900">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7 fill-current text-indigo-700" viewBox="0 0 20 20" >
                    <path d="M10.394 2.08a1 1 0 00-.788 0l-7 3a1 1 0 000 1.84L5.25 8.051a.999.999 0 01.356-.257l4-1.714a1 1 0 11.788 1.838L7.667 9.088l1.94.831a1 1 0 00.787 0l7-3a1 1 0 000-1.838l-7-3zM3.31 9.397L5 10.12v4.102a8.969 8.969 0 00-1.05-.174 1 1 0 01-.89-.89 11.115 11.115 0 01.25-3.762zM9.3 16.573A9.026 9.026 0 007 14.935v-3.957l1.818.78a3 3 0 002.364 0l5.508-2.361a11.026 11.026 0 01.25 3.762 1 1 0 01-.89.89 8.968 8.968 0 00-5.35 2.524 1 1 0 01-1.4 0zM6 18a1 1 0 001-1v-2.065a8.935 8.935 0 00-2-.712V17a1 1 0 001 1z" />
                </svg>
                <p class="font-extrabold text-lg font-serif text-blue-900">Secondary</p>
            </div>
            <div class="px-6 text-xs text-stone-700">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Minima a dolor consectetur odit cum.</div>
            <div class="px-6 absolute bottom-4 font-bold font-serif text-xs text-blue-900 cursor-pointer hover:text-gray-700">Secondary Education -></div>
        </div>
        <div class="bg-sky-100 relative w-full h-48 border-b-4 border-yellow-300">
            <img src="/jpg/academics_01.jpg" alt="caro_1" class="object-cover h-full w-full ">
            <div class="absolute top-0 bg-blue-900 bg-opacity-20 h-full w-full flex cursor-pointer hover:bg-opacity-0 transition duration-150"></div>

        </div>
        <div class="bg-sky-100 relative w-full h-48 border-b-4 border-red-500">
            <img src="/jpg/academics_02.jpg" alt="caro_1" class="object-cover h-full w-full  ">
            <div class="absolute top-0 bg-blue-900 bg-opacity-20 h-full w-full flex cursor-pointer hover:bg-opacity-0 transition duration-150"></div>

        </div>
        <div class="bg-sky-100 relative w-full h-48 mero border-b-4 border-indigo-900 ">
            <img src="/jpg/academics_03.jpg" alt="caro_1" class="object-cover h-full w-full mero ">
            <div class="absolute top-0 bg-blue-900 bg-opacity-20 h-full w-full flex cursor-pointer hover:bg-opacity-0 transition duration-150"></div>

        </div>

    </div>
</section>

<section>
    <div class="flex py-10 md:w-full md:px-8 xl:w-4/6 mx-auto ">
        <div class="h-40 w-full px-2 md:w-3/5 md:px-0 bg-white">
            <div class="pt-4 font-extrabold text-xl text-center font-serif text-blue-900 ">About NIS</div>
            <div class="text-center px-2 text-xs lg:text-sm pt-4 text-stone-600">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae hic eveniet qui neque nemo tempore quas accusantium quod impedit architecto! Ducimus ea odio itaque, 
                optio nihil eaque eum magni harum!</div>
        </div>
        <div class="hidden md:block h-40 w-2/5 bg-teal-400 relative">
            <img src="/jpg/about_01.jpg" alt="caro_1" class="object-cover h-full w-full ">
            <div class="absolute top-0 bg-blue-900 opacity-10 cursor-pointer hover:opacity-0 transition duration-150 w-full h-full z-10"></div>
        </div>

    </div>
</section>

<section class="hidden md:block">
    <div class="w-full h-32 bg-stone-100"></div>
</section>

<section class="my-0 lg:my-10">
    <div class="h-auto  w-full xl:w-5/6  mx-auto grid xl:px-4 gap-x-6 grid-cols-1 lg:grid-cols-3 ">
        <div class="hidden lg:block h-full bg-teal-400 shadow-md relative">
            <div class="absolute bg-blue-900 h-full w-full top-0 opacity-5 hover:opacity-0 transition duration-300 cursor-pointer"></div>
            <img src="/jpg/contacts_01.jpg" alt="caro_1" class="object-cover h-full w-full ">
        </div>
        <div class="hidden lg:block h-full bg-slate-500 shadow-md relative">
            <div class="absolute bg-blue-900 h-full w-full top-0 opacity-5 hover:opacity-0 transition duration-300 cursor-pointer"></div>
            <img src="/jpg/contacts_02.jpg" alt="caro_1" class="object-cover h-full w-full ">
        </div>
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

<section class="hidden md:block mb-10">
    <div class="w-full h-32 bg-stone-100"></div>
</section>

<div class="map bg-blue-100 h-96 border border-stone-500 mb-8 w-5/6 mx-auto">
    <iframe title="loc" src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d15902.512103228504!2d6.9652381!3d4.8337655!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x73e01499b99781a9!2sNithalos%20Montessori%20School!5e0!3m2!1sen!2sng!4v1659693295841!5m2!1sen!2sng" 
    class="h-full w-full" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</div>

<section>

</section>


<style>
    .texture{
        background-color: #1a0369;
        background-color: #1a0369;
background-image: url("data:image/svg+xml,%3Csvg width='42' height='44' viewBox='0 0 42 44' xmlns='http://www.w3.org/2000/svg'%3E%3Cg id='Page-1' fill='none' fill-rule='evenodd'%3E%3Cg id='brick-wall' fill='%233b58d5' fill-opacity='0.14'%3E%3Cpath d='M0 0h42v44H0V0zm1 1h40v20H1V1zM0 23h20v20H0V23zm22 0h20v20H22V23z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
    }


</style>
<template>
    <div id="app">
        <component :is="currentMenu" :right="side === 'right' ? true: false" class="fixed z-30 md:hidden">
            <a href="#hello">
                <i class="fa fa-fw fa-star-o"></i>
                <span>Hello</span>
            </a>
            <a href="#resume">
                <i class="fa fa-fw fa-bell-o"></i>
                <span>Resume</span>
            </a>
            <a href="#portofolio">
                <i class="fa fa-fw fa-envelope-o"></i>
                <span>Portofolio</span>
            </a>
            <a href="#contact">
                <i class="fa fa-fw fa-comment-o"></i>
                <span>Contacts</span>
            </a>

        </component>
        <main id="page-wrap">
        <div>
          <div class="bg-blue-700 w-full fixed z-50 hidden md:block">
                    <div class="flex px-2 py-8 ">
                      <a href="#hello" class="text-white text-xl font-extralight mx-8">
                        Hello
                      </a>
                      <a href="#resume" class="text-white text-xl font-extralight  mx-8">
                        Resume
                      </a>
                      <a href="#portofolio" class="text-white text-xl font-extralight  mx-8">
                        Portofolio
                      </a>
                      <a href="#contact" class="text-white text-xl font-extralight  mx-8">
                        Contacts
                      </a>

                    </div>
          </div>
          <div class="">
           <div class="bg-blue-500 ">
              `     <div class="" id="hello">
                          <div class="flex min-h-screen justify-center items-center relative p-2 mt-4" >
              <div class="relative max-w-4xl">
                  <div
                      class="absolute z-10 inset-0 bg-gradient-to-r from-blue-400 to-blue-800 shadow-lg transform -skew-y-6 sm:skew-y-0 sm:-rotate-6 sm:rounded-lg"
                  ></div>
                  <div
                      class="relative z-20 bg-white md:flex justify-between p-12 shadow-lg rounded-lg w-full max-w-4xl"
                  >
                      <div
                          class="sm:flex flex-col justify-between space-y-6 py-6 md:pr-10"
                      >
                          <div >
                              <h2 class="text-lg">Hello, I am </h2>
                              <h1 class="pt-1 text-4xl font-bold text-gray-800">
                                  Muhammad Miftah
                              </h1>
                          </div>
                          <p class="text-xl leading-relaxed">
                            Junior Web Devoloper, terbiasa membangun aplikasi website menggunakan Laravel, Vue Js dan Tailwind CSS
                          </p>
                          <div class="inline-flex text-xl text-gray-600 space-x-5" >
                              <a href="https://github.com/chmiftah/"><img src="icons/logo-github.svg" class="w-6"></a>
                               <a href="https://www.linkedin.com/in/muhammad-miftah-choirul-habibi-79376b131/"><img src="icons/logo-linkedin.svg" class="w-6"></a>
                                <a href="#"><img src="icons/logo-facebook.svg" class="w-6"></a>
                                 <a href="#"><img src="icons/logo-twitter.svg" class="w-6"></a>

                          </div>
                      </div>

                        <img
                          src="images/bg-profiles.jpg"
                          alt=""
                          class="flex-shrink-0 w-80 rounded-full border-6 border-white shadow-md"
                      />


                  </div>
              </div>
                        </div>
                    </div>
              </div>
          </div>

          <div class="px-24 py-12" id="resume">
            <div class="text-6xl font font-semi bold mt-12">Hi_</div>
            <div class="mt-4 text-2xl font-light w-full md:w-3/4">Seorang Web Devoloper yang terbiasa membangun aplikasi website menggunakan <strong>Laravel</strong>, <strong>Vue Js</strong> dan <strong>Tailwind CSS</strong>, serta mampu menulis kode yang dirancang dengan baik dan efisen. Seorang yang mudah dalam <strong>belajar</strong> hal baru, <strong>pekerja keras</strong>, <strong>bertanggung jawab</strong> dan baik dalam <strong>Kerjasama Tim.</strong></div>
            <button class="mt-4 bg-blue-500 hover:bg-blue-600 rounded-lg px-5 py-2 border border-white text-white focus:outline-none text-xl">Download CV</button>
          </div>
           <hr>
          <div class="pl-24 pr-6 py-12">

                    <div class="text-3xl font-semibold mt-12 mb-6">EDUCATION</div>
                    <div class="relative w-full md:w-1/2 my-4">
                      <div class="border-r-2 border-blue-500 absolute h-full top-0" style="left: 10px"></div>
                      <ul class="list-none m-0 p-0">
                        <li class="mb-2">
                          <div class="flex items-center mb-1">
                            <div class="bg-white rounded-full border-2 border-blue-500 h-6 w-6 z-10"></div>
                            <div class="flex-1 ml-4 font-light text-xl">UNIVERSITAS AHMAD DAHLAN YOGYAKARTA</div>
                          </div>
                            <div class="ml-12 font-light text-lg">
                          Teknik Informatika
                          </div>
                          <div class="ml-12 font-light text-lg mb-8">
                            2016-2020
                          </div>

                        </li>

                        <li class="mb-2">
                          <div class="flex items-center mb-1">
                            <div class="bg-white rounded-full border-2 border-blue-500 h-6 w-6 z-10"></div>
                            <div class="flex-1 ml-4 font-light text-xl">SMA NEGERI 1 CAWAS KLATEN</div>
                          </div>
                          <div class="ml-12 font-light text-lg">
                            MIPA
                          </div>
                          <div class="ml-12 mb-8 font-light text-lg">
                          2013-2016
                          </div>
                        </li>


                        <li class="mb-2">
                          <div class="flex items-center mb-1">
                            <div class="bg-white rounded-full border-2 border-blue-500 h-6 w-6 z-10"></div>
                            <div class="flex-1 ml-4 font-light text-xl">SMP NEGERI 1 BAYAT KLATEN</div>
                          </div>
                          <div class="ml-12 mr-8 font-light text-lg">
                            2013-2016
                          </div>

                        </li>

                      </ul>
                    </div>

                    <div class="text-3xl font-semibold mt-12 mb-6 ">EMPLOYE</div>
                    <div class="relative w-full  my-4">
                            <div class="border-r-2 border-blue-500 absolute h-full top-0" style="left: 10px"></div>
                            <ul class="list-none m-0 p-0">
                              <li class="mb-2">
                                <div class="flex items-center mb-1">
                                  <div class="bg-white rounded-full border-2 border-blue-500 h-6 w-6 z-10"></div>
                                  <div class="flex-1 ml-4 font-light text-xl">OLC EDUKASI (Remote Job)</div>
                                </div>
                                <div class="ml-12 font-light text-lg">
                                  Pengembangan aplikasi web (Company Profile, Sistem Pendaftaran)
                                </div>
                                <div class="ml-12 mb-8 font-light text-lg">
                                2020 - 2021 (Remote)
                                </div>
                              </li>

                              <li class="mb-2">
                                <div class="flex items-center mb-1">
                                  <div class="bg-white rounded-full border-2 border-blue-500 h-6 w-6 z-10"></div>
                                  <div class="flex-1 ml-4 font-light text-2xl">Jackskin Yogyakarta (Kerja Praktek)</div>
                                </div>
                                <div class="ml-12 font-light text-lg">
                                  Pengembangan Aplikasi Berbasis Website (Ecommerce)

                                </div>
                                <div class="ml-12 mb-8 font-light text-lg">
                                Apr 2018 - Oct 2018
                                </div>
                              </li>


                              <li class="mb-2">
                                <div class="flex items-center mb-1 ">
                                  <div class="bg-white rounded-full border-2 border-blue-500 h-6 w-6 z-10"></div>
                                  <div class="flex-1 ml-4 font-light text-2xl">Pusat Pengelolaan Elearning (PPE) Universitas Ahmad Dahlan (Magang)</div>
                                </div>
                                <div class="ml-12 font-light text-lg">
                                  Pengelolaan dan pembuatan konten pembelajaran Elearning Universitas Ahmad Dahlan
                                </div>
                                <div class="ml-12 font-light text-lg">
                                  jan 2017- juli 2017
                                </div>

                              </li>

                            </ul>
                    </div>
                      <div class="text-3xl font-semibold mt-12 mb-6 ">CERTIFICATED</div>
                    <div class="relative w-full  my-4">
                            <div class="border-r-2 border-blue-500 absolute h-full top-0" style="left: 10px"></div>
                            <ul class="list-none m-0 p-0">

                              <li class="mb-2">
                                <div class="flex items-center mb-1">
                                  <div class="bg-white rounded-full border-2 border-blue-500 h-6 w-6 z-10"></div>
                                  <div class="flex-1 ml-4 font-light text-2xl">Programer Komputer - Pengembangan Aplikasi Web</div>
                                </div>
                                <div class="ml-12 font-light text-lg">
                                 Badan Nasional Sertifikasi Profesi Indonesia (BNSP)
                                 No. 62010 2513.06 6 0000626 2020

                                </div>
                                <div class="ml-12 mb-8 font-light text-lg">
                                November 2020
                                </div>
                              </li>


                              <li class="mb-2">
                                <div class="flex items-center mb-1 ">
                                  <div class="bg-white rounded-full border-2 border-blue-500 h-6 w-6 z-10"></div>
                                  <div class="flex-1 ml-4 font-light text-2xl">Sistem Pengelolaan Data - Database Administrator</div>
                                </div>
                                <div class="ml-12 font-light text-lg">
                                  Badan Nasional Sertifikasi Profesi Indonesia (BNSP)
                                 No. 62010 2512.04 6 0000313 2020
                                </div>
                                <div class="ml-12 font-light text-lg">
                                  Oktober 2020
                                </div>

                              </li>

                            </ul>
                    </div>
          </div>

          <div href="#resume" class="px-24 mb-12">
            <div class="text-3xl font font-semibold">GENERAL SKILLS</div>
            <div class="flex w-full  py-4 ">
              <div class="w-1/2 pr-4">

                <div>
                <div>HTML</div>
                <div class="relative pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-pink-200">
                  <div style="width:80%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-blue-500"></div>
                </div>
                </div>
                </div>

                 <div>
                <div>CSS</div>
                <div class="relative pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-pink-200">
                  <div style="width:60%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-blue-500"></div>
                </div>
                </div>
                </div>

                 <div>
                <div>BOOTSTRAP</div>
                <div class="relative pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-pink-200">
                  <div style="width:80%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-blue-500"></div>
                </div>
                </div>
                </div>

                 <div>
                <div>TAILWIND CSS</div>
                <div class="relative pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-pink-200">
                  <div style="width:70%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-blue-500"></div>
                </div>
                </div>
                </div>

                    <div>
                <div>MYSQL</div>
                <div class="relative pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-pink-200">
                  <div style="width:70%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-blue-500"></div>
                </div>
                </div>
                </div>

                     <div>
                <div>WORDPRESS</div>
                <div class="relative pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-pink-200">
                  <div style="width:60%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-blue-500"></div>
                </div>
                </div>
                </div>

              </div>
              <div class="w-1/2  pl-8">

                <div>
                <div>PHP</div>
                <div class="relative pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-pink-200">
                  <div style="width:60%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-blue-500"></div>
                </div>
                </div>
                </div>

                 <div>
                <div>LARAVEL</div>
                <div class="relative pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-pink-200">
                  <div style="width:70%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-blue-500"></div>
                </div>
                </div>
                </div>


                 <div>
                <div>CODE IGNITER</div>
                <div class="relative pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-pink-200">
                  <div style="width:30%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-blue-500"></div>
                </div>
                </div>
                </div>

                 <div>
                <div>VUE JS</div>
                <div class="relative pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-pink-200">
                  <div style="width:50%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-blue-500"></div>
                </div>
                </div>
                </div>

                     <div>
                <div>REACT JS</div>
                <div class="relative pt-1">
                <div class="overflow-hidden h-2 mb-4 text-xs flex rounded bg-pink-200">
                  <div style="width:20%" class="shadow-none flex flex-col text-center whitespace-nowrap text-white justify-center bg-blue-500"></div>
                </div>
                </div>
                </div>

              </div>
            </div>
          </div>
        <hr>
          <div class="px-6 md:px-24 mt-12" id="portofolio">
              <div class="text-5xl font font-semi bold"  style="font-family:Inconsolata">My Projects_</div>
                <div class="border border-gray-100 shadow-sm mx-4 my-8 p-2">
                  <div class="flex flex-col md:flex-row mt-6">
                <div class="w-full md:w-1/2 p-2">
                  <img src="images/anime.png" alt="" class="rounded-lg h-80 w-full">
                </div>
                <div class="w-full md:w-3/4 p-6">
                  <div class="text-3xl font-semibold mb-6" style="font-family:Inconsolata">
                    AnimeTV - Anime List and Movie Information
                  </div>
                  <div class="text-xl font-light">
                   List of anime and its details. Built with Vue Js and Tailwindcss, API fetched from jikan.moe.
                  </div>
                  <div class="mt-6">
                    <div class="mb-4 font-light">Used Stack:</div>
                    <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-2 text-sm">VueJs 2</span>
                         <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-2  text-sm">Tailwind CSS</span>
                          <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-2  text-sm">API</span>


                  </div>
                  <div class="my-6" style="font-family:Inconsolata">
                    link: <a class="text-blue-600" href="https://myanime-tv.netlify.app/">https://myanime-tv.netlify.app/</a>
                  </div>
                </div>
              </div>
                </div>
                <div class="border border-gray-100 shadow-sm mx-4 my-8 p-2">
                  <div class="flex flex-col md:flex-row mt-6">
                <div class="w-full md:w-1/2 p-2">
                  <img src="images/movie.png" alt="" class="rounded-lg h-80 w-full">
                </div>
                <div class="w-full md:w-3/4 p-6">
                  <div class="text-3xl font-semibold mb-6" style="font-family:Inconsolata">
                    MoviHub - Movie Information App
                  </div>
                  <div class="text-xl font-light">
                  Movie app where you can discover movies or tv shows. Built with VueJS 3, vuex, vuer-router, Composition API & Tailwind CSS, API from themoviedb
                  </div>
                  <div class="mt-6">
                    <div class="mb-4 font-light">Used Stack:</div>
                    <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-2  text-sm">VueJs 3</span>
                         <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-2  text-sm">Tailwind CSS</span>
                              <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-2  text-sm">API</span>

                  </div>
                  <div class="my-6" style="font-family:Inconsolata">
                    link: <a class="text-blue-600" href="https://movi-hub.netlify.app/">https://movi-hub.netlify.app/</a>
                  </div>
                </div>
              </div>
                </div>
                <div class="border border-gray-100 shadow-sm mx-4 my-8 p-2">
                  <div class="flex flex-col md:flex-row mt-6">
                <div class="w-full md:w-1/2 p-2">
                  <img src="images/quran.png" alt="" class="rounded-lg w-full h-80">
                </div>
                <div class="w-full md:w-3/4 p-6">
                  <div class="text-3xl font-semibold mb-6" style="font-family:Inconsolata">
                    Quran-Online  (Read & listen Quran Online)
                  </div>
                  <div class="text-xl font-light">
                        Read and Listen to Qur'an online. Built with VueJS 2 and TailwindCSS, Api from sutanlab.com
                  </div>
                  <div class="mt-6">
                    <div class="mb-4 font-light">Used Stack:</div>
                    <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-2  text-sm">VueJs2</span>
                         <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-2  text-sm">Tailwind CSS</span>

                                   <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-2  text-sm">Api</span>
                  </div>
                  <div class="my-6" style="font-family:Inconsolata">
                    link: <a class="text-blue-600" href="https://idquran.netlify.app/">https://idquran.netlify.app/</a>
                  </div>
                </div>
              </div>
                </div>
                 <div class="border border-gray-100 shadow-sm mx-4 my-8 p-2">
                  <div class="flex flex-col md:flex-row mt-6">
                <div class="w-full md:w-1/2 p-2">
                  <img src="images/elapor.png" alt="" class="rounded-lg h-80 w-full">
                </div>
                    <div class="w-full md:w-3/4 p-6">
                  <div class="text-3xl font-semibold mb-6" style="font-family:Inconsolata">
                   Elapor -  Sistem Informasi Pengaduan Masyarakat
                  </div>
                  <div class="text-xl font-light">
                       build using Laravel 8, Livewire, Tailwind CSS and Alpine Js
                  </div>
                  <div class="mt-6">
                    <div class="mb-4 font-light">Used Stack:</div>
                    <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-1  text-sm">Laravel</span>
                         <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-1  text-sm">Tailwind Css</span>
                                   <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-1  text-sm">AlpineJs</span>
                  </div>
                  <div class="my-6" style="font-family:Inconsolata">
                    link: <a class="text-blue-600" href="">-</a>
                  </div>
                </div>


              </div>
                </div>

                  <div class="border border-gray-100 shadow-sm mx-4 my-8 p-2">
                  <div class="flex flex-col md:flex-row mt-6">
                <div class="w-full md:w-1/2 p-2">
                  <img src="images/sosmed.png" alt="" class="rounded-lg h-80 w-full">
                </div>
                    <div class="w-full md:w-3/4 p-6">
                  <div class="text-3xl font-semibold mb-6" style="font-family:Inconsolata">
                   Friendster - Mini Social Media App
                  </div>
                  <div class="text-xl font-light">
                       you can share status, write comment and follow your friend, build using Laravel 8, Livewire, Tailwind CSS and Alpine Js
                  </div>
                  <div class="mt-6">
                    <div class="mb-4 font-light">Used Stack:</div>
                      <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-1  text-sm">Laravel</span>
                         <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-1  text-sm">Tailwind Css</span>
                                   <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-1  text-sm">AlpineJs</span>
                  </div>
                  <div class="my-6" style="font-family:Inconsolata">
                    link: <a href="" class="text-blue-600"></a>
                  </div>
                </div>


              </div>
                </div>

                        <div class="border border-gray-100 shadow-sm mx-4 my-8 p-2">
                  <div class="flex flex-col md:flex-row mt-6">
                <div class="w-full md:w-1/2 p-2">
                  <img src="images/olc.png" alt="" class="rounded-lg  h-80 w-full">
                </div>
                    <div class="w-full md:w-3/4 p-2">
                  <div class="text-3xl font-semibold mb-6" style="font-family:Inconsolata">
                   Olcedukasi.com - Company Profile and  Blog Portal
                  </div>
                  <div class="text-xl font-light">
                      Olcedukasi.com web company profile and blog, build using Code Igniter 3.
                  </div>
                  <div class="mt-6">
                    <div class="mb-4 font-light">Used Stack:</div>
                    <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-1  text-sm">CI</span>
                         <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-1  text-sm">BOOTSTRAP</span>
                              <span class=" px-2 py-1 rounded-lg border-2 border-gray-100  shadow-md mr-1  text-sm">AJAX</span>

                  </div>
                  <div class="my-6" style="font-family:Inconsolata">
                    link: <a class="text-blue-600" href="https://olcedukasi.com">https://olcedukasi.com</a>
                  </div>
                </div>


              </div>
                </div>












          </div>

        <section class="pt-20 pb-36 px-8 bg-blue-600" id="contact">
            <div class="max-w-6xl mx-auto">
                <div class="text-center">
                    <h1 class="text-6xl font-bold text-white">Contact</h1>
                    <p class="pt-2 text-white">Get in touch with me</p>
                </div>
            </div>
            <div class="mt-16 relative max-w-4xl mx-auto">
                <div
                    class="absolute z-10 inset-0 bg-gradient-to-r from-cyan-400 to-emerald-400 shadow-lg transform -skew-y-6 sm:skew-y-0 sm:-rotate-6 sm:rounded-lg"
                ></div>
                <div class="relative z-20 bg-white rounded-md shadow-md p-12">
                    <form action="">
                        <div
                            class="grid grid-cols-1 md:grid-cols-2 gap-x-8 gap-y-6"
                        >
                            <input
                                type="text"
                                placeholder="Name"
                                class="border border-gray-200 outline-none px-4 py-2 rounded-md hover:border-gray-400 focus:border-gray-400"
                            />
                            <input
                                type="text"
                                placeholder="Email"
                                class="border border-gray-200 outline-none px-4 py-2 rounded-md hover:border-gray-400 focus:border-gray-400"
                            />
                            <input
                                type="text"
                                placeholder="Subject"
                                class="border border-gray-200 outline-none px-4 py-2 rounded-md hover:border-gray-400 focus:border-gray-400 md:col-span-2"
                            />
                            <textarea
                                rows="5"
                                placeholder="Message"
                                class="border border-gray-200 outline-none px-4 py-2 rounded-md hover:border-gray-400 focus:border-gray-400 md:col-span-2"
                            ></textarea>
                        </div>
                        <button
                            class="inline-block w-auto mt-4 px-6 py-2 bg-gradient-to-r from-blue-400 to-blue-700 rounded-md shadow-md text-sm font-bold text-white"
                        >
                            Send Message
                        </button>
                    </form>
                </div>
            </div>
        </section>
      </div>

        </main>
    </div>
</template>
 <script src="https://unpkg.com/ionicons@5.2.3/dist/ionicons.js"></script>
<script>
    import slide from './components/Menu/slide';
    import bubble from './components/Menu/bubble';
    import elastic from './components/Menu/elastic';
    import falldown from './components/Menu/fallDown';
    import push from './components/Menu/push';
    import pushrotate from './components/Menu/pushRotate';
    import reveal from './components/Menu/reveal';
    import scaledown from './components/Menu/scaleDown';
    import scalerotate from './components/Menu/scaleRotate';
    import stack from './components/Menu/stack';
    import Menu from './components/Menu';

    export default {
      data() {
        return {
          menus: {
            slide: { buttonText: 'Slide' },
            push: { buttonText: 'Push' },
            pushRotate: { buttonText: 'Push Rotate' },
            reveal: { buttonText: 'Reveal' },
            scaleDown: { buttonText: 'Scale Down' },
            scaleRotate: { buttonText: 'Scale Rotate' },
            // elastic: { buttonText: 'Elastic - (WIP)' },
            // stack: { buttonText: 'Stack - (WIP)' },
            bubble: { buttonText: 'Bubble' },
            fallDown: { buttonText: 'Fall Down' }
          },
          side: 'left',
          currentMenu: 'slide'
        };
      },
      components: {
        slide,
        bubble,
        elastic,
        push,
        pushrotate,
        scaledown,
        scalerotate,
        reveal,
        stack,
        falldown,
        Menu
      },
      methods: {
        changeMenu(menu) {
          this.currentMenu = menu.replace(/ +/g, '').toLowerCase();
          return this.currentMenu;
        },
        changeSide(side) {
          this.side = side;
        }
      }
    };
</script>

 <style>

    .demo-buttons {
      font-size: 1em;
      max-width: 1200px;
      margin: 2em auto 3em;
      padding: 0 10em;

      a {
        display: inline-block;
        margin: 0.75em;
        padding: 1.35em 1.1em;
        width: 15em;
        background: #fffce1;
        text-transform: uppercase;
        letter-spacing: 1px;
        font-weight: 800;
        border-top-left-radius: 20px 50px;
        border-top-right-radius: 20px 50px;
        border-bottom-right-radius: 20px 50px;
        border-bottom-left-radius: 20px 50px;
        cursor: pointer;

        &.currentDemo {
          background: #c94e50;
          color: #fffce1;
        }
      }
    }

    .sideButton {
      display: inline-block;
      width: 5em;
      height: 2.5em;
      line-height: 2.5em;
      cursor: pointer;
      background: #fffce1;
      text-transform: uppercase;
      letter-spacing: 1px;
      font-size: 0.8em;
      font-weight: 800;

      &.left {
        border-top-left-radius: 10px;
        border-bottom-left-radius: 10px;
      }

      &.right {
        border-top-right-radius: 10px;
        border-bottom-right-radius: 10px;
      }

      &.active {
        background: #c94e50;
        color: #fffce1;
      }
    }

    @media screen and (max-width: 40em) {
      main {
        font-size: 80%;
      }

      h1 {
        padding-top: 1em;
        font-size: 2.5em;
      }

      .demo-buttons {
        max-width: 900px;
        padding: 0 2em;
      }
    }

    //
    // Burger menu custom styles
    //
    .bm-burger-button {
      position: absolute;
      width: 36px;
      height: 30px;
      left: 36px;
      top: 36px;

    }

    .right .bm-burger-button {
      left: initial;
      right: 36px;
    }

    .bm-burger-bars {
      background: #373a47;
    }

    .bm-morph-shape {
      fill: #373a47;
    }

    .bm-menu {
      background: #373a47;

      a {
        color: #b8b7ad;

        &:hover,
        &:focus {
          color: #c94e50;
        }
      }
    }

    //
    // Mixins
    //
    .menu-1 {
      .bm-cross {
        background: #bdc3c7;
      }

      .bm-menu {
        padding: 2.5em 1.5em 0;
        font-size: 1.15em;
      }
    }
</style>

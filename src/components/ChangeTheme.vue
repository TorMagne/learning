<template>
  <div class="flex-0">
    <div class="items-center flex-none hidden">
      <a sveltekit:prefetch="" href="/components" class="btn btn-ghost drawer-button normal-case"
        ><svg width="20" height="20" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="inline-block h-6 w-6 fill-current md:mr-2">
          <path
            d="M6.5,22 C4.01471863,22 2,19.9852814 2,17.5 C2,15.0147186 4.01471863,13 6.5,13 C8.98528137,13 11,15.0147186 11,17.5 C11,19.9852814 8.98528137,22 6.5,22 Z M17.5,22 C15.0147186,22 13,19.9852814 13,17.5 C13,15.0147186 15.0147186,13 17.5,13 C19.9852814,13 22,15.0147186 22,17.5 C22,19.9852814 19.9852814,22 17.5,22 Z M6.5,11 C4.01471863,11 2,8.98528137 2,6.5 C2,4.01471863 4.01471863,2 6.5,2 C8.98528137,2 11,4.01471863 11,6.5 C11,8.98528137 8.98528137,11 6.5,11 Z M17.5,11 C15.0147186,11 13,8.98528137 13,6.5 C13,4.01471863 15.0147186,2 17.5,2 C19.9852814,2 22,4.01471863 22,6.5 C22,8.98528137 19.9852814,11 17.5,11 Z M17.5,9 C18.8807119,9 20,7.88071187 20,6.5 C20,5.11928813 18.8807119,4 17.5,4 C16.1192881,4 15,5.11928813 15,6.5 C15,7.88071187 16.1192881,9 17.5,9 Z M6.5,9 C7.88071187,9 9,7.88071187 9,6.5 C9,5.11928813 7.88071187,4 6.5,4 C5.11928813,4 4,5.11928813 4,6.5 C4,7.88071187 5.11928813,9 6.5,9 Z M17.5,20 C18.8807119,20 20,18.8807119 20,17.5 C20,16.1192881 18.8807119,15 17.5,15 C16.1192881,15 15,16.1192881 15,17.5 C15,18.8807119 16.1192881,20 17.5,20 Z M6.5,20 C7.88071187,20 9,18.8807119 9,17.5 C9,16.1192881 7.88071187,15 6.5,15 C5.11928813,15 4,16.1192881 4,17.5 C4,18.8807119 5.11928813,20 6.5,20 Z"
          ></path>
        </svg>
        Components</a
      >
    </div>
    <div title="Change Theme" class="dropdown dropdown-end">
      <div tabindex="0" class="btn gap-1 normal-case btn-ghost">
        <svg width="20" height="20" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" class="inline-block h-5 w-5 stroke-current md:h-6 md:w-6"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21a4 4 0 01-4-4V5a2 2 0 012-2h4a2 2 0 012 2v12a4 4 0 01-4 4zm0 0h12a2 2 0 002-2v-4a2 2 0 00-2-2h-2.343M11 7.343l1.657-1.657a2 2 0 012.828 0l2.829 2.829a2 2 0 010 2.828l-8.486 8.485M7 17h.01"></path></svg> <span class="hidden md:inline">Theme</span>
        <svg width="12px" height="12px" class="ml-1 hidden h-3 w-3 fill-current opacity-60 sm:inline-block" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2048 2048"><path d="M1799 349l242 241-1017 1017L7 590l242-241 775 775 775-775z"></path></svg>
      </div>
      <div class="dropdown-content bg-base-200 text-base-content rounded-t-box rounded-b-box top-px max-h-96 h-[70vh] w-52 overflow-y-auto shadow-2xl mt-16">
        <div class="grid grid-cols-1 gap-3 p-3" tabindex="0">
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="light" data-act-class="outline">
            <div data-theme="light" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">light</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2 outline" data-set-theme="dark" data-act-class="outline">
            <div data-theme="dark" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">dark</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="cupcake" data-act-class="outline">
            <div data-theme="cupcake" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">cupcake</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="bumblebee" data-act-class="outline">
            <div data-theme="bumblebee" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">bumblebee</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="emerald" data-act-class="outline">
            <div data-theme="emerald" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">emerald</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="corporate" data-act-class="outline">
            <div data-theme="corporate" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">corporate</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="synthwave" data-act-class="outline">
            <div data-theme="synthwave" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">synthwave</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="retro" data-act-class="outline">
            <div data-theme="retro" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">retro</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="cyberpunk" data-act-class="outline">
            <div data-theme="cyberpunk" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">cyberpunk</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="valentine" data-act-class="outline">
            <div data-theme="valentine" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">valentine</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="halloween" data-act-class="outline">
            <div data-theme="halloween" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">halloween</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="garden" data-act-class="outline">
            <div data-theme="garden" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">garden</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="forest" data-act-class="outline">
            <div data-theme="forest" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">forest</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="aqua" data-act-class="outline">
            <div data-theme="aqua" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">aqua</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="lofi" data-act-class="outline">
            <div data-theme="lofi" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">lofi</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="pastel" data-act-class="outline">
            <div data-theme="pastel" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">pastel</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="fantasy" data-act-class="outline">
            <div data-theme="fantasy" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">fantasy</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="wireframe" data-act-class="outline">
            <div data-theme="wireframe" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">wireframe</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="black" data-act-class="outline">
            <div data-theme="black" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">black</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="luxury" data-act-class="outline">
            <div data-theme="luxury" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">luxury</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="dracula" data-act-class="outline">
            <div data-theme="dracula" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">dracula</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="cmyk" data-act-class="outline">
            <div data-theme="cmyk" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">cmyk</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="autumn" data-act-class="outline">
            <div data-theme="autumn" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">autumn</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="business" data-act-class="outline">
            <div data-theme="business" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">business</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="acid" data-act-class="outline">
            <div data-theme="acid" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">acid</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="lemonade" data-act-class="outline">
            <div data-theme="lemonade" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">lemonade</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="night" data-act-class="outline">
            <div data-theme="night" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">night</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="coffee" data-act-class="outline">
            <div data-theme="coffee" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">coffee</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="outline-base-content overflow-hidden rounded-lg outline-2 outline-offset-2" data-set-theme="winter" data-act-class="outline">
            <div data-theme="winter" class="bg-base-100 text-base-content w-full cursor-pointer font-sans">
              <div class="grid grid-cols-5 grid-rows-3">
                <div class="col-span-5 row-span-3 row-start-1 flex gap-1 py-3 px-4">
                  <div class="flex-grow text-sm font-bold">winter</div>
                  <div class="flex flex-shrink-0 flex-wrap gap-1">
                    <div class="bg-primary w-2 rounded"></div>
                    <div class="bg-secondary w-2 rounded"></div>
                    <div class="bg-accent w-2 rounded"></div>
                    <div class="bg-neutral w-2 rounded"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

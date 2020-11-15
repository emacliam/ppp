<template>
  <main class="bg-hero max-w-full">
    <div
      class="modal h-screen w-full absolute z-50  justify-center items-center bg-black bg-opacity-50 hidden"
    >
      <!-- modal -->
      <div class="bg-white rounded shadow-lg w-10/12">
        <!-- modal header -->
        <div class="border-b px-4 py-2 flex justify-between items-center">
          <h3 class="font-semibold text-lg">CONTACT US</h3>
          <button class="text-black close-modal">&cross;</button>
        </div>
        <div class="pt-4 pb-4 text-xs">
          <div class="max-w-full flex md:flex-col mx-8">
            <div class="w-1/2 h-24">
              <div class="md:flex items-center justify-between ">
                <div class="flex flex-col">
                  <div class="">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-10 w-10"
                      viewBox="0 0 32 32"
                    >
                      <g transform="translate(0 -1020.362)">
                        <path
                          fill="#f05542"
                          style="line-height:normal;text-indent:0;text-align:start;text-decoration-line:none;text-decoration-style:solid;text-decoration-color:#000;text-transform:none;block-progression:tb;isolation:auto;mix-blend-mode:normal"
                          d="M1.4960938 1036.3555a.50004997.50004997 0 0 0-.4824219.5156c.1418706 7.9343 6.5556887 14.3393 14.4902341 14.4687a.50007724.50007724 0 1 0 .01758-1C8.1152146 1050.219 2.1460968 1044.2596 2.0136719 1036.8535a.50004997.50004997 0 0 0-.5175781-.498zM12.101562 1044.3984a.50004997.50004997 0 0 0-.279296.918c1.08906.7367 2.38781 1.1012 3.701172 1.0391a.50004997.50004997 0 1 0-.04688-.9981c-1.097889.052-2.183361-.2533-3.09375-.8691a.50004997.50004997 0 0 0-.28125-.09z"
                          color="#000"
                          font-family="sans-serif"
                          font-weight="400"
                          overflow="visible"
                          white-space="normal"
                        />
                        <path
                          fill="#f05542"
                          fill-rule="evenodd"
                          style="line-height:normal;text-indent:0;text-align:start;text-decoration-line:none;text-decoration-style:solid;text-decoration-color:#000;text-transform:none;block-progression:tb;isolation:auto;mix-blend-mode:normal"
                          d="M15.503906 1045.3516a.50005.50005 0 0 0-.492187.5078l0 4.9824a.50005.50005 0 1 0 1 0l0-4.9824a.50005.50005 0 0 0-.507813-.5078zM12.025391 1044.3672a.50005.50005 0 0 0-.429688.2754l-.01953.041a.50005.50005 0 0 0-.002 0l-.957031 1.8555a.50005.50005 0 1 0 .888671.457l.957032-1.8535.02148-.041a.50005.50005 0 0 0-.458984-.7363z"
                          color="#000"
                          font-family="sans-serif"
                          font-weight="400"
                          overflow="visible"
                          white-space="normal"
                        />
                        <path
                          fill="#f05542"
                          style="line-height:normal;text-indent:0;text-align:start;text-decoration-line:none;text-decoration-style:solid;text-decoration-color:#000;text-transform:none;block-progression:tb;isolation:auto;mix-blend-mode:normal"
                          d="M7.9941406 1040.2715a.50004997.50004997 0 0 1-.9179687.2793c-.7388844-1.0923-1.103844-2.3957-1.0390625-3.7129a.50004997.50004997 0 1 1 .9980468.049c-.054153 1.1011.2514776 2.1904.8691407 3.1035a.50004997.50004997 0 0 1 .089844.2813zM11.544922 1046.791a.50004994.50004994 0 0 1-.716797.4238c-2.5024799-1.1689-4.5100249-3.1868-5.6660156-5.6953a.50028714.50028714 0 1 1 .9082031-.4199c1.0571347 2.294 2.8931632 4.14 5.1816405 5.209a.50004994.50004994 0 0 1 .292969.4824z"
                          color="#000"
                          font-family="sans-serif"
                          font-weight="400"
                          overflow="visible"
                          white-space="normal"
                        />
                        <path
                          fill="#f05542"
                          fill-rule="evenodd"
                          style="line-height:normal;text-indent:0;text-align:start;text-decoration-line:none;text-decoration-style:solid;text-decoration-color:#000;text-transform:none;block-progression:tb;isolation:auto;mix-blend-mode:normal"
                          d="M1.4902344 1036.3633a.50059569.50059569 0 0 0 .048828 1l4.9179687 0a.50005.50005 0 1 0 0-1l-4.9179687 0a.50005.50005 0 0 0-.048828 0zM7.5214844 1039.8281a.50005.50005 0 0 0-.2246094.059l-1.9140625.9805a.5000661.5000661 0 1 0 .4550781.8906l1.9140625-.9805a.50005.50005 0 0 0-.2304687-.9492z"
                          color="#000"
                          font-family="sans-serif"
                          font-weight="400"
                          overflow="visible"
                          white-space="normal"
                        />
                        <path
                          fill="#f05542"
                          style="line-height:125%;-inkscape-font-specification:'Bebas Neue Bold'"
                          d="M17.98796 1029.9715c0 2.4423-2.63579 2.8534-2.63579 5.3441l0 1.0398 3.84487 0 0-1.209-2.51488 0c-.0121-.06-.0121-.1209-.0121-.1814 0-1.3904 2.64788-2.3819 2.64788-5.0419 0-1.3541-.67708-2.1279-1.98289-2.1279-1.30581 0-1.98289.7738-1.98289 2.1279l0 .8222 1.25744 0 0-.9068c0-.6045.266-.8343.68918-.8343.42318 0 .68917.2056.68917.9673zM19.83162 1034.8199l2.56325 0 0 1.5355 1.3058 0 0-1.5355.62872 0 0-1.2091-.62872 0 0-5.7189-1.45089 0-2.41816 5.7189 0 1.2091zm1.22117-1.2091l1.34208-3.1799 0 3.1799-1.34208 0z"
                          font-family="Bebas Neue"
                          font-size="12.091"
                          font-weight="700"
                          letter-spacing="0"
                          word-spacing="0"
                        />
                        <path
                          fill="#2b4255"
                          style="line-height:normal;text-indent:0;text-align:start;text-decoration-line:none;text-decoration-style:solid;text-decoration-color:#000;text-transform:none;block-progression:tb;isolation:auto;mix-blend-mode:normal"
                          d="m 16.835938,1021.3867 c -7.5964432,-0.4242 -14.3135583,4.9202 -15.6054692,12.418 a 0.5004271,0.5004271 0 1 0 0.9863281,0.1699 c 1.2070444,-7.0052 7.4650721,-11.9862 14.5625001,-11.5898 7.097424,0.3963 12.762124,6.0425 13.181641,13.1386 0.41955,7.0962 -4.539711,13.3717 -11.541016,14.6016 a 0.50004997,0.50004997 0 1 0 0.171875,0.9844 c 7.493561,-1.3164 12.818189,-8.0495 12.369141,-15.6446 -0.449013,-7.595 -6.528562,-13.6538 -14.125,-14.0781 z"
                          color="#000"
                          font-family="sans-serif"
                          font-weight="400"
                          overflow="visible"
                          white-space="normal"
                        />
                        <path
                          fill="#2b4255"
                          style="line-height:normal;text-indent:0;text-align:start;text-decoration-line:none;text-decoration-style:solid;text-decoration-color:#000;text-transform:none;block-progression:tb;isolation:auto;mix-blend-mode:normal"
                          d="m 10.517578,1040.3574 a 0.50005,0.50005 0 1 0 0,1 c 0.282027,0 0.499986,0.218 0.5,0.5 a 0.50005,0.50005 0 1 0 1,0 c -4.1e-5,-0.8224 -0.677551,-1.5 -1.5,-1.5 z"
                          color="#000"
                          font-family="sans-serif"
                          font-weight="400"
                          opacity=".97"
                          overflow="visible"
                          white-space="normal"
                        />
                        <path
                          fill="#2b4255"
                          style="line-height:normal;text-indent:0;text-align:start;text-decoration-line:none;text-decoration-style:solid;text-decoration-color:#000;text-transform:none;block-progression:tb;isolation:auto;mix-blend-mode:normal"
                          d="m 10.523438,1038.3574 a 0.50005,0.50005 0 1 0 0,1 c 1.384024,0 2.49417,1.1121 2.49414,2.4961 a 0.50005,0.50005 0 1 0 1,0 c 4.2e-5,-1.9245 -1.569669,-3.4961 -3.49414,-3.4961 z"
                          color="#000"
                          font-family="sans-serif"
                          font-weight="400"
                          opacity=".97"
                          overflow="visible"
                          white-space="normal"
                        />
                        <path
                          fill="#2b4255"
                          style="line-height:normal;text-indent:0;text-align:start;text-decoration-line:none;text-decoration-style:solid;text-decoration-color:#000;text-transform:none;block-progression:tb;isolation:auto;mix-blend-mode:normal"
                          d="m 10.525391,1036.3555 a 0.50005,0.50005 0 1 0 0,1 c 2.488392,0 4.494126,2.0077 4.49414,4.4961 a 0.50005,0.50005 0 1 0 1,0 c -1.7e-5,-3.0289 -2.46531,-5.4961 -5.49414,-5.4961 z"
                          color="#000"
                          font-family="sans-serif"
                          font-weight="400"
                          opacity=".97"
                          overflow="visible"
                          white-space="normal"
                        />
                        <path
                          fill="#f05542"
                          fill-rule="evenodd"
                          style="line-height:normal;text-indent:0;text-align:start;text-decoration-line:none;text-decoration-style:solid;text-decoration-color:#000;text-transform:none;block-progression:tb;isolation:auto;mix-blend-mode:normal"
                          d="m 25.28448,1034.8604 0,1 1.5625,0 -1.45117,3.6172 0.92968,0.3731 1.72461,-4.3047 a 0.50005,0.50005 0 0 0 -0.46484,-0.6856 l -2.30078,0 z"
                          color="#000"
                          font-family="sans-serif"
                          font-weight="400"
                          overflow="visible"
                          white-space="normal"
                        />
                      </g>
                    </svg>
                  </div>
                </div>
                <div class="flex flex-col">
                  <div>
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      data-name="Layer 1"
                      viewBox="0 0 168 168"
                      class="w-10 h-10"
                    >
                      <circle cx="2" cy="147.5" r="2" fill="#2d4356" />
                      <path
                        fill="#2d4356"
                        d="M11,145.5H8a2,2,0,0,0,0,4h3a2,2,0,0,0,0-4Z"
                      />
                      <path
                        fill="#0bceb2"
                        d="M118.15387 153.5h-8.30774a2.00641 2.00641 0 0 0 0 4h8.30774a2.00641 2.00641 0 0 0 0-4zM58.15387 153.5H49.84613a2.00641 2.00641 0 0 0 0 4h8.30774a2.00641 2.00641 0 0 0 0-4zM104 153.5H64a2 2 0 0 0 0 4H79.94v2H72a2 2 0 0 0 0 4H97a2 2 0 0 0 0-4H88.06v-2H104a2 2 0 0 0 0-4zM133.6709 81.6153a1.99966 1.99966 0 0 0-2.77-.57239L87.84473 109.40332a6.0883 6.0883 0 0 1-6.84668.01569L37.09277 80.7511a2.0017 2.0017 0 0 0-2.18555 3.35419L78.813 112.77222a10.10439 10.10439 0 0 0 11.23047-.0235l43.05566-28.36041A2.00368 2.00368 0 0 0 133.6709 81.6153zM60.95166 111.75647l-26 16.01715a2.00145 2.00145 0 1 0 2.09668 3.40985l26-16.01709a2.00147 2.00147 0 0 0-2.09668-3.40991zM133.04834 127.77362l-26-16.01715a2.00147 2.00147 0 0 0-2.09668 3.40991l26 16.01709a2.00145 2.00145 0 0 0 2.09668-3.40985z"
                      />
                      <path
                        fill="#2d4356"
                        d="M54.56177,84.60455a8.06628,8.06628,0,0,0,7.60229,5.3847,7.93646,7.93646,0,0,0,2.59644-.437l58.95276-20.373a8.00066,8.00066,0,0,0,4.92548-10.17438l-11.2005-32.12018A8.06617,8.06617,0,0,0,109.83594,21.5a7.93967,7.93967,0,0,0-2.59644.437L48.28674,42.31a8.00071,8.00071,0,0,0-4.92548,10.17438ZM47.32007,48.123A3.94374,3.94374,0,0,1,49.592,46.095l58.95276-20.37292a3.94471,3.94471,0,0,1,1.29156-.21777,4.04644,4.04644,0,0,1,3.82538,2.70013l11.20056,32.12018a3.99558,3.99558,0,0,1-2.45422,5.06964L63.45526,85.76721a3.94578,3.94578,0,0,1-1.2912.21777,4.04684,4.04684,0,0,1-3.82574-2.7002L47.13776,51.16467A3.95,3.95,0,0,1,47.32007,48.123Z"
                      />
                      <path
                        fill="#0bceb2"
                        d="M56.40186 51.65649l25.90479 6.592a8.45228 8.45228 0 0 0 8.8252-3.08289L106.99561 34.2951a2.00082 2.00082 0 1 0-3.18359-2.42444L87.94824 52.74115A4.46343 4.46343 0 0 1 83.292 54.36737l-25.90479-6.592a2.00212 2.00212 0 0 0-.98535 3.8811zM96.56738 55.88464A2.00258 2.00258 0 0 0 97.98486 58.335l15 4.00427a2.0021 2.0021 0 0 0 1.03027-3.86938l-15-4.00427A2.00133 2.00133 0 0 0 96.56738 55.88464zM75.46338 62.12616l-10 12.01288a2.001 2.001 0 1 0 3.07324 2.56329l10-12.01288a2.001 2.001 0 1 0-3.07324-2.56329z"
                      />
                      <path
                        fill="#2d4356"
                        d="M160,145.5h-3a2,2,0,0,0,0,4h3a2,2,0,0,0,0-4Z"
                      />
                      <circle cx="166" cy="147.5" r="2" fill="#2d4356" />
                      <path
                        fill="#2d4356"
                        d="M150.72131 145.5h-3.81183A7.93654 7.93654 0 0 0 148 141.49139V75.42065a8.02778 8.02778 0 0 0-8-8.00854h-8.42273a11.89242 11.89242 0 0 1-3.55133 4.00427H140a4.00667 4.00667 0 0 1 4 4.00427v66.07074a4.00672 4.00672 0 0 1-4 4.00433H28a4.00672 4.00672 0 0 1-4-4.00433V75.42065a4.00667 4.00667 0 0 1 4-4.00427H45.72638l-1.3963-4.00427H28a8.02778 8.02778 0 0 0-8 8.00854v66.07074A7.93654 7.93654 0 0 0 21.09052 145.5H17.27869a2.017 2.017 0 1 0 0 4H150.72131a2.017 2.017 0 1 0 0-4zM32.30471 11.5a3 3 0 1 0-3-3A3.00344 3.00344 0 0 0 32.30471 11.5zm0-4.5a1.5 1.5 0 1 1-1.5 1.5A1.50148 1.50148 0 0 1 32.30471 7zM149.30471 59.5a2 2 0 1 0 2 2A2.00229 2.00229 0 0 0 149.30471 59.5zm0 3a1 1 0 1 1 1-1A1.001 1.001 0 0 1 149.30471 62.5zM132.30471 30.5a2 2 0 1 0 2 2A2.00229 2.00229 0 0 0 132.30471 30.5zm0 3a1 1 0 1 1 1-1A1.001 1.001 0 0 1 132.30471 33.5zM152.30471 4.5a2 2 0 1 0 2 2A2.00229 2.00229 0 0 0 152.30471 4.5zm0 3a1 1 0 1 1 1-1A1.001 1.001 0 0 1 152.30471 7.5zM24.30471 51.5a2 2 0 1 0-2 2A2.00229 2.00229 0 0 0 24.30471 51.5zm-3 0a1 1 0 1 1 1 1A1.001 1.001 0 0 1 21.30471 51.5z"
                      />
                      <polygon
                        fill="#0bceb2"
                        points="4.888 25.511 6.375 23.556 5.436 23.024 4.481 25.214 4.45 25.214 3.48 23.039 2.525 23.587 3.996 25.496 3.996 25.527 1.695 25.23 1.695 26.294 4.011 25.997 4.011 26.028 2.525 27.936 3.416 28.5 4.434 26.294 4.465 26.294 5.404 28.484 6.39 27.921 4.888 26.043 4.888 26.012 7.25 26.294 7.25 25.23 4.888 25.542 4.888 25.511"
                      />
                      <polygon
                        fill="#0bceb2"
                        points="58.081 25.567 57.225 26.666 57.739 26.99 58.325 25.72 58.342 25.72 58.883 26.981 59.451 26.657 58.586 25.575 58.586 25.557 59.946 25.72 59.946 25.107 58.586 25.287 58.586 25.269 59.442 24.143 58.902 23.837 58.352 25.098 58.334 25.098 57.775 23.845 57.225 24.161 58.072 25.26 58.072 25.278 56.747 25.107 56.747 25.72 58.081 25.549 58.081 25.567"
                      />
                      <polygon
                        fill="#0bceb2"
                        points="164.305 41.213 164.305 40.17 161.988 40.477 161.988 40.446 163.446 38.528 162.525 38.006 161.589 40.154 161.558 40.154 160.607 38.021 159.67 38.559 161.113 40.431 161.113 40.462 158.856 40.17 158.856 41.213 161.128 40.922 161.128 40.953 159.67 42.825 160.545 43.378 161.543 41.213 161.573 41.213 162.494 43.362 163.461 42.81 161.988 40.968 161.988 40.937 164.305 41.213"
                      />
                      <polygon
                        fill="#0bceb2"
                        points="86.748 10.086 88.006 8.431 87.211 7.981 86.404 9.834 86.377 9.834 85.557 7.994 84.748 8.458 85.993 10.073 85.993 10.099 84.047 9.848 84.047 10.748 86.006 10.496 86.006 10.523 84.748 12.138 85.503 12.615 86.364 10.748 86.39 10.748 87.185 12.601 88.019 12.125 86.748 10.536 86.748 10.509 88.746 10.748 88.746 9.848 86.748 10.112 86.748 10.086"
                      />
                    </svg>
                  </div>
                </div>
              </div>
            </div>
            <form action="" class="form bg-white relative w-1/2 ">
              <div class="flex space-x-1 mt-3 w-full">
                <input
                  type="text"
                  name=""
                  id=""
                  placeholder="Your Name"
                  class="border p-2 w-1/2 focus:border-teal-400"
                />
                <input
                  type="tel"
                  name=""
                  id=""
                  placeholder="Your Number"
                  class="border p-2 w-1/2 focus:border-teal-400"
                />
              </div>
              <input
                type="email"
                name=""
                id=""
                placeholder="Your Email"
                class="border p-2 w-full mt-3 focus:border-teal-400"
              />
              <textarea
                name=""
                id=""
                cols="10"
                rows="3"
                placeholder="Tell us about desired property"
                class="border p-2 mt-3 w-full focus:border-teal-400"
              ></textarea>
              <input
                type="submit"
                value="Submit"
                class="w-full mt-6 bg-teal-600 hover:bg-teal-500 text-white font-semibold p-1"
              />
            </form>
          </div>
        </div>
      </div>
    </div>
    <div
      class="nav w-full bg-blue-800 justify-between items-start pl-2 pr-32 pt-2 text-white"
      :style="image"
    >
      `
      <div class="flex w-full justify-between items-start">
        <div class="flex">
          <div class="text-4xl text-teal-500">
            OMNAI
          </div>
        </div>
        <div class="text-xs">
          <nuxt-link class="mx-4 hover:text-teal-400 font-semibold" to="/"
            >Home</nuxt-link
          >
          <nuxt-link class="mx-4 hover:text-teal-400 font-semibold" to="/about"
            >About</nuxt-link
          >
          <nuxt-link
            class="mx-4 hover:text-teal-400 font-semibold"
            to="/services"
            >Services</nuxt-link
          >
          <nuxt-link class="mx-4 hover:text-teal-400 font-semibold" to="/works"
            >Works</nuxt-link
          >
          <nuxt-link
            class="mx-4 hover:text-teal-400 font-semibold"
            to="/pricing"
            >pricing</nuxt-link
          >
          <button class="bg-teal-400 py-3 px-8 show-modal">
            Contact Now
          </button>
        </div>
      </div>
      `
      <div class="mt-16 ml-24 flex flex-col opacity-75">
        us .....
      </div>
      <div class="text-3xl text-center">
        <h1
          v-if="$nuxt.$route.name == 'about'"
          id="page-caption"
          class="font-semibold"
        >
          About Us
        </h1>
        <h1
          v-if="$nuxt.$route.name == 'services'"
          id="page-caption"
          class="font-semibold "
        >
          Our Services
        </h1>
        <h1
          v-if="$nuxt.$route.name == 'works'"
          id="page-caption"
          class="font-semibold"
        >
          Our Recent Projects
        </h1>
        <h1
          v-if="$nuxt.$route.name == 'pricing'"
          id="page-caption"
          class="font-semibold"
        >
          Pricing
        </h1>
      </div>
    </div>
    <div
      :class="{ scrolled: view.atTopOfPage }"
      class=" tp fixed w-full flex items-center  px-32 h-16  z-10 top-0 text-xs bg-gradient-to-r from-blue-300 via-blue-400 to-blue-500"
    >
      <div class="flex items-center justify-between pt-2 text-white">
        <div class="flex items-center">
          LOGO HERE
          <span class="my-2 text-center font-bold text-lg">omnai</span>
        </div>
        <div>
          <nuxt-link class="mx-4 hover:text-teal-400 font-semibold" to="/"
            >Home</nuxt-link
          >
          <nuxt-link class="mx-4 hover:text-teal-400 font-semibold" to="/about"
            >About</nuxt-link
          >
          <nuxt-link
            class="mx-4 hover:text-teal-400 font-semibold"
            to="/services"
            >Services</nuxt-link
          >
          <nuxt-link class="mx-4 hover:text-teal-400 font-semibold" to="/works"
            >Works</nuxt-link
          >
          <nuxt-link
            class="mx-4 hover:text-teal-400 font-semibold"
            to="/pricing"
            >Pricing</nuxt-link
          >
        </div>
      </div>
    </div>
    <div class="pt-24 max-w-full m-auto">
      <nuxt />
    </div>
    <footer class=" pb-8" :style="image">
      <!-- component -->
      <div class="bg-gray-100">
        <div
          class="max-w-6xl m-auto text-gray-800 flex flex-wrap justify-center"
        >
          <div class="p-5 w-48 ">
            <div class="text-xs uppercase text-gray-500 font-medium">Home</div>
            <a class="my-3 block" href="/#"
              >Services <span class="text-teal-600 text-xs p-1"></span></a
            ><a class="my-3 block" href="/#"
              >Products <span class="text-teal-600 text-xs p-1"></span></a
            ><a class="my-3 block" href="/#"
              >About Us <span class="text-teal-600 text-xs p-1"></span></a
            ><a class="my-3 block" href="/#"
              >Pricing <span class="text-teal-600 text-xs p-1"></span></a
            ><a class="my-3 block" href="/#"
              >Partners <span class="text-teal-600 text-xs p-1">New</span></a
            >
          </div>
          <div class="p-5 w-48 ">
            <div class="text-xs uppercase text-gray-500 font-medium">User</div>
            <a class="my-3 block" href="/#"
              >Sign in <span class="text-teal-600 text-xs p-1"></span></a
            ><a class="my-3 block" href="/#"
              >New Account <span class="text-teal-600 text-xs p-1"></span></a
            ><a class="my-3 block" href="/#"
              >Demo <span class="text-teal-600 text-xs p-1">New</span></a
            ><a class="my-3 block" href="/#"
              >Career
              <span class="text-teal-600 text-xs p-1">We're hiring</span></a
            ><a class="my-3 block" href="/#"
              >Surveys <span class="text-teal-600 text-xs p-1">New</span></a
            >
          </div>
          <div class="p-5 w-48 ">
            <div class="text-xs uppercase text-gray-500 font-medium">
              Resources
            </div>
            <a class="my-3 block" href="/#"
              >Documentation <span class="text-teal-600 text-xs p-1"></span></a
            ><a class="my-3 block" href="/#"
              >Tutorials <span class="text-teal-600 text-xs p-1"></span></a
            ><a class="my-3 block" href="/#"
              >Support <span class="text-teal-600 text-xs p-1">New</span></a
            >
          </div>
          <div class="p-5 w-48 ">
            <div class="text-xs uppercase text-gray-500 font-medium">
              Product
            </div>
            <a class="my-3 block" href="/#"
              >Our Products <span class="text-teal-600 text-xs p-1"></span></a
            ><a class="my-3 block" href="/#"
              >Great Deals <span class="text-teal-600 text-xs p-1">New</span></a
            ><a class="my-3 block" href="/#"
              >Analytics <span class="text-teal-600 text-xs p-1"></span></a
            ><a class="my-3 block" href="/#"
              >Mobile <span class="text-teal-600 text-xs p-1"></span
            ></a>
          </div>
          <div class="p-5 w-48 ">
            <div class="text-xs uppercase text-gray-500 font-medium">
              Support
            </div>
            <a class="my-3 block" href="/#"
              >Help Center <span class="text-teal-600 text-xs p-1"></span></a
            ><a class="my-3 block" href="/#"
              >Privacy Policy <span class="text-teal-600 text-xs p-1"></span></a
            ><a class="my-3 block" href="/#"
              >Conditions <span class="text-teal-600 text-xs p-1"></span
            ></a>
          </div>
          <div class="p-5 w-48 ">
            <div class="text-xs uppercase text-gray-500 font-medium">
              Contact us
            </div>
            <a class="my-3 block" href="/#"
              >XXX XXXX, Floor 4 San Francisco, CA
              <span class="text-teal-600 text-xs p-1"></span></a
            ><a class="my-3 block" href="/#"
              >contact@company.com
              <span class="text-teal-600 text-xs p-1"></span
            ></a>
          </div>
        </div>
      </div>

      <div class="bg-gray-100 pt-2 ">
        <div
          class="flex pb-5 px-3 m-auto pt-5 border-t text-gray-800 text-sm flex-col
      md:flex-row max-w-6xl"
        >
          <div class="mt-2">© Copyright 2020. All Rights Reserved.</div>
          <div class="md:flex-auto md:flex-row-reverse mt-2 flex-row flex">
            <a href="/#" class="w-6 mx-1">
              <svg
                class="fill-current cursor-pointer text-gray-500 hover:text-gray-400"
                width="100%"
                height="100%"
                viewBox="0 0 24 24"
                version="1.1"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
                xml:space="preserve"
                xmlns:serif="http://www.serif.com/"
                style="fill-rule: evenodd; clip-rule: evenodd; stroke-linejoin: round; stroke-miterlimit: 2;"
              >
                <path
                  id="Twitter"
                  d="M24,12c0,6.627 -5.373,12 -12,12c-6.627,0 -12,-5.373 -12,-12c0,-6.627
                  5.373,-12 12,-12c6.627,0 12,5.373 12,12Zm-6.465,-3.192c-0.379,0.168
                  -0.786,0.281 -1.213,0.333c0.436,-0.262 0.771,-0.676
                  0.929,-1.169c-0.408,0.242 -0.86,0.418 -1.341,0.513c-0.385,-0.411
                  -0.934,-0.667 -1.541,-0.667c-1.167,0 -2.112,0.945 -2.112,2.111c0,0.166
                  0.018,0.327 0.054,0.482c-1.754,-0.088 -3.31,-0.929
                  -4.352,-2.206c-0.181,0.311 -0.286,0.674 -0.286,1.061c0,0.733 0.373,1.379
                  0.94,1.757c-0.346,-0.01 -0.672,-0.106 -0.956,-0.264c-0.001,0.009
                  -0.001,0.018 -0.001,0.027c0,1.023 0.728,1.877 1.694,2.07c-0.177,0.049
                  -0.364,0.075 -0.556,0.075c-0.137,0 -0.269,-0.014 -0.397,-0.038c0.268,0.838
                  1.048,1.449 1.972,1.466c-0.723,0.566 -1.633,0.904 -2.622,0.904c-0.171,0
                  -0.339,-0.01 -0.504,-0.03c0.934,0.599 2.044,0.949 3.237,0.949c3.883,0
                  6.007,-3.217 6.007,-6.008c0,-0.091 -0.002,-0.183 -0.006,-0.273c0.413,-0.298
                  0.771,-0.67 1.054,-1.093Z"
                ></path>
              </svg>
            </a>
            <a href="/#" class="w-6 mx-1">
              <svg
                class="fill-current cursor-pointer text-gray-500 hover:text-gray-400"
                width="100%"
                height="100%"
                viewBox="0 0 24 24"
                version="1.1"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
                xml:space="preserve"
                xmlns:serif="http://www.serif.com/"
                style="fill-rule: evenodd; clip-rule: evenodd; stroke-linejoin: round; stroke-miterlimit: 2;"
              >
                <path
                  id="Facebook"
                  d="M24,12c0,6.627 -5.373,12 -12,12c-6.627,0 -12,-5.373 -12,-12c0,-6.627
                  5.373,-12 12,-12c6.627,0 12,5.373
                  12,12Zm-11.278,0l1.294,0l0.172,-1.617l-1.466,0l0.002,-0.808c0,-0.422
                  0.04,-0.648 0.646,-0.648l0.809,0l0,-1.616l-1.295,0c-1.555,0 -2.103,0.784
                  -2.103,2.102l0,0.97l-0.969,0l0,1.617l0.969,0l0,4.689l1.941,0l0,-4.689Z"
                ></path>
              </svg>
            </a>
            <a href="/#" class="w-6 mx-1">
              <svg
                class="fill-current cursor-pointer text-gray-500 hover:text-gray-400"
                width="100%"
                height="100%"
                viewBox="0 0 24 24"
                version="1.1"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
                xml:space="preserve"
                xmlns:serif="http://www.serif.com/"
                style="fill-rule: evenodd; clip-rule: evenodd; stroke-linejoin: round; stroke-miterlimit: 2;"
              >
                <g id="Layer_1">
                  <circle id="Oval" cx="12" cy="12" r="12"></circle>
                  <path
                    id="Shape"
                    d="M19.05,8.362c0,-0.062 0,-0.125 -0.063,-0.187l0,-0.063c-0.187,-0.562
                     -0.687,-0.937 -1.312,-0.937l0.125,0c0,0 -2.438,-0.375 -5.75,-0.375c-3.25,0
                     -5.75,0.375 -5.75,0.375l0.125,0c-0.625,0 -1.125,0.375
                     -1.313,0.937l0,0.063c0,0.062 0,0.125 -0.062,0.187c-0.063,0.625 -0.25,1.938
                     -0.25,3.438c0,1.5 0.187,2.812 0.25,3.437c0,0.063 0,0.125
                     0.062,0.188l0,0.062c0.188,0.563 0.688,0.938 1.313,0.938l-0.125,0c0,0
                     2.437,0.375 5.75,0.375c3.25,0 5.75,-0.375 5.75,-0.375l-0.125,0c0.625,0
                     1.125,-0.375 1.312,-0.938l0,-0.062c0,-0.063 0,-0.125
                     0.063,-0.188c0.062,-0.625 0.25,-1.937 0.25,-3.437c0,-1.5 -0.125,-2.813
                     -0.25,-3.438Zm-4.634,3.927l-3.201,2.315c-0.068,0.068 -0.137,0.068
                     -0.205,0.068c-0.068,0 -0.136,0 -0.204,-0.068c-0.136,-0.068 -0.204,-0.204
                     -0.204,-0.34l0,-4.631c0,-0.136 0.068,-0.273 0.204,-0.341c0.136,-0.068
                     0.272,-0.068 0.409,0l3.201,2.316c0.068,0.068 0.136,0.204
                     0.136,0.34c0.068,0.136 0,0.273 -0.136,0.341Z"
                    style="fill: rgb(255, 255, 255);"
                  ></path>
                </g>
              </svg>
            </a>
            <a href="/#" class="w-6 mx-1">
              <svg
                class="fill-current cursor-pointer text-gray-500 hover:text-gray-400"
                width="100%"
                height="100%"
                viewBox="0 0 24 24"
                version="1.1"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
                xml:space="preserve"
                xmlns:serif="http://www.serif.com/"
                style="fill-rule: evenodd; clip-rule: evenodd; stroke-linejoin: round; stroke-miterlimit: 2;"
              >
                <path
                  id="Shape"
                  d="M7.3,0.9c1.5,-0.6 3.1,-0.9 4.7,-0.9c1.6,0 3.2,0.3 4.7,0.9c1.5,0.6 2.8,1.5
                  3.8,2.6c1,1.1 1.9,2.3 2.6,3.8c0.7,1.5 0.9,3 0.9,4.7c0,1.7 -0.3,3.2
                  -0.9,4.7c-0.6,1.5 -1.5,2.8 -2.6,3.8c-1.1,1 -2.3,1.9 -3.8,2.6c-1.5,0.7
                  -3.1,0.9 -4.7,0.9c-1.6,0 -3.2,-0.3 -4.7,-0.9c-1.5,-0.6 -2.8,-1.5
                  -3.8,-2.6c-1,-1.1 -1.9,-2.3 -2.6,-3.8c-0.7,-1.5 -0.9,-3.1 -0.9,-4.7c0,-1.6
                  0.3,-3.2 0.9,-4.7c0.6,-1.5 1.5,-2.8 2.6,-3.8c1.1,-1 2.3,-1.9
                  3.8,-2.6Zm-0.3,7.1c0.6,0 1.1,-0.2 1.5,-0.5c0.4,-0.3 0.5,-0.8 0.5,-1.3c0,-0.5
                  -0.2,-0.9 -0.6,-1.2c-0.4,-0.3 -0.8,-0.5 -1.4,-0.5c-0.6,0 -1.1,0.2
                  -1.4,0.5c-0.3,0.3 -0.6,0.7 -0.6,1.2c0,0.5 0.2,0.9 0.5,1.3c0.3,0.4 0.9,0.5
                  1.5,0.5Zm1.5,10l0,-8.5l-3,0l0,8.5l3,0Zm11,0l0,-4.5c0,-1.4 -0.3,-2.5
                  -0.9,-3.3c-0.6,-0.8 -1.5,-1.2 -2.6,-1.2c-0.6,0 -1.1,0.2 -1.5,0.5c-0.4,0.3
                  -0.8,0.8 -0.9,1.3l-0.1,-1.3l-3,0l0.1,2l0,6.5l3,0l0,-4.5c0,-0.6 0.1,-1.1
                  0.4,-1.5c0.3,-0.4 0.6,-0.5 1.1,-0.5c0.5,0 0.9,0.2 1.1,0.5c0.2,0.3 0.4,0.8
                  0.4,1.5l0,4.5l2.9,0Z"
                ></path>
              </svg>
            </a>
            <a href="/#" class="w-6 mx-1">
              <svg
                class="fill-current cursor-pointer text-gray-500 hover:text-gray-400"
                width="100%"
                height="100%"
                viewBox="0 0 24 24"
                version="1.1"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
                xml:space="preserve"
                xmlns:serif="http://www.serif.com/"
                style="fill-rule: evenodd; clip-rule: evenodd; stroke-linejoin: round; stroke-miterlimit: 2;"
              >
                <path
                  id="Combined-Shape"
                  d="M12,24c6.627,0 12,-5.373 12,-12c0,-6.627 -5.373,-12 -12,-12c-6.627,0
                  -12,5.373 -12,12c0,6.627 5.373,12 12,12Zm6.591,-15.556l-0.722,0c-0.189,0
                  -0.681,0.208 -0.681,0.385l0,6.422c0,0.178 0.492,0.323
                  0.681,0.323l0.722,0l0,1.426l-4.675,0l0,-1.426l0.935,0l0,-6.655l-0.163,0l-2.251,8.081l-1.742,0l-2.222,-8.081l-0.168,0l0,6.655l0.935,0l0,1.426l-3.74,0l0,-1.426l0.519,0c0.203,0
                  0.416,-0.145 0.416,-0.323l0,-6.422c0,-0.177 -0.213,-0.385
                  -0.416,-0.385l-0.519,0l0,-1.426l4.847,0l1.583,5.704l0.042,0l1.598,-5.704l5.021,0l0,1.426Z"
                ></path>
              </svg>
            </a>
          </div>
        </div>
      </div>
    </footer>
  </main>
</template>

<script>
import hero from "assets/h1_hero.jpg";
export default {
  layout: "none",
  data() {
    return {
      isMobile: Boolean,
      view: {
        atTopOfPage: false,
        lastScrollPosition: 200
      },
      image: { backgroundImage: `url(${hero})` }
    };
  },
  asyncData({ isMobile }) {
    return {
      isMobile: isMobile
    };
  },

  // a beforeMount call to add a listener to the window
  beforeMount() {
    window.addEventListener("scroll", this.handleScroll);
  },

  methods: {
    // the function to call when the user scrolls, added as a method
    handleScroll() {
      const currentScrollPosition =
        window.pageYOffset || document.documentElement.scrollTop;
      console.log(currentScrollPosition > Number(this.view.lastScrollPosition));
      if (Math.abs(currentScrollPosition > this.view.lastScrollPosition)) {
        this.view.atTopOfPage = true;
      } else {
        this.view.atTopOfPage = false;
      }
    }
  },
  mounted() {
    const modal = document.querySelector(".modal");

    const showModal = document.querySelector(".show-modal");
    const closeModal = document.querySelectorAll(".close-modal");

    showModal.addEventListener("click", function() {
      modal.classList.remove("hidden");
    });

    closeModal.forEach(close => {
      close.addEventListener("click", function() {
        modal.classList.add("hidden");
      });
    });
  }
};
</script>

<style scoped>
.tp {
  z-index: 10;
  display: none;
}

.tp.scrolled {
  display: block;
  border-bottom: 0px;
}

.btm {
  z-index: 10;
}

.btm.scrolled {
  @apply hidden;
  border-bottom: 0px;
}
.nuxt-link-exact-active {
  border-bottom: 2px teal solid;
  padding: 2px;
}
.head {
  background-image: url("/h2_hero.jpg");
}
.nav {
  height: 35rem;
}
.modal {
  padding-top: 5vh;
  padding-left: 30vh;
}
.icon::after {
  content: "";
  display: block;
  position: absolute;
  border-top: 23px solid transparent;
  border-bottom: 17px solid transparent;
  border-left: 12px solid #3182ce;
  left: 100%;
  top: 0;
}
.ft {
  padding-left: 0;
}
.ft:hover {
  padding-left: 10px;
  transition: padding-left 0.5s ease-in;
}
</style>

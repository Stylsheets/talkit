<template>
  <nav class="flex flex-shrink-0 justify-between w-full bg-white px-20 items-center h-20 border-b border-slate-50 shadow-md z-10">
    <div class="w-full max-w-7xl mx-auto flex items-center h-full">
      <div class="flex h-full items-center">
        <div class="pr-6 h-12 flex-shrink-0">
            <img src="../assets/logo.svg" class="h-full w-full" alt="logo">
        </div>
        <div
          class="flex bg-gray-50 h-14 w-72 px-4 items-center rounded-xl"
        >
          <input
            class="bg-gray-50 mr-8 outline-none border-none text-gray-400"
            type="text"
            placeholder="Type to search"
          />
          <a
            href="#"
            class="bg-white h-10 w-10 rounded-xl flex items-center justify-center border border-gray-200"
          >
            <svg
              class="text-gray-600"
              xmlns="http://www.w3.org/2000/svg"
              width="18"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <circle cx="11" cy="11" r="8"></circle>
              <line x1="21" y1="21" x2="16.65" y2="16.65"></line>
            </svg>
          </a>
        </div>
      </div>
      <div class="flex items-center h-full relative">
        <a href="#" class="mx-10 text-lg font-semibold text-gray-400">Grades</a>
        <a href="#" class="mx-10 text-lg font-semibold text-gray-400"
          >Schedule</a
        >
        <a href="#" class="mx-10 text-lg font-semibold text-gray-400"
          >Comunnity</a
        >
        <div class="relative h-full flex items-center">
          <a href="#" class="mx-10 text-lg font-semibold text-gray-700"
            >Payments</a
          >
          <span
            class="block absolute bg-[#543FDD] bottom-0 transform translate-x-10 w-20 h-0.5"
          ></span>
        </div>
        <a href="#" class="mx-10 text-lg font-semibold text-gray-400">Grades</a>
        <a
          class="h-9 w-9 mr-14 relative rounded-xl border border-gray-300 flex justify-center items-center bg-gray-100"
          href="#"
        >
          <span
            class="block bg-[#543FDD] h-2.5 w-2.5 rounded-full absolute top-0 right-0 transform translate-y-1 -translate-x-0.5"
          ></span>
          <svg
            class="text-gray-400"
            xmlns="http://www.w3.org/2000/svg"
            width="18"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path
              d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"
            ></path>
            <polyline points="22,6 12,13 2,6"></polyline>
          </svg>
        </a>
        <a href="#">
          <svg
            class="text-gray-400"
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path>
            <circle cx="12" cy="7" r="4"></circle>
          </svg>
        </a>
      </div>
    </div>
  </nav>
</template>
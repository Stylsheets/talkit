<template>
  <div class="relative h-full flex flex-col">
    <!-- 3 column wrapper -->
    <div class="w-full h-full max-w-7xl mx-auto lg:flex">
      <div class="w-full xl:flex">
        <div class="xl:flex-shrink-0 xl:w-64 xl:border-r xl:border-gray-200">
          <div class="pl-4 pr-6 py-6 sm:pl-6 lg:pl-8 xl:pl-0">
             <!--- Left Sidebar -->
          </div>
        </div>

        <div class="bg-white lg:min-w-0 lg:flex-1">
            <div class="p-10">
              <div class="mb-5 py-1 px-3 flex justify-between items-center bg-gray-100 rounded-lg">
                  <input type="text" placeholder="Add a new thread" class="focus:ring-0 rounded-l-lg bg-gray-100 w-full border-none focus:border-none">
                  <a href="#" class="h-9 w-9 flex-shrink-0 bg-[#5441D8] rounded-xl flex justify-center items-center">                  
                    <svg xmlns="http://www.w3.org/2000/svg" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-white"><line x1="12" y1="5" x2="12" y2="19"></line><line x1="5" y1="12" x2="19" y2="12"></line></svg>
                  </a>
              </div>
              <div class="bg-gray-100 p-8 mb-5 rounded-xl">
              <h1 class="text-4xl font-semibold pb-8">Lecture Rescheduling</h1>
              <div class="flex justify-between items-center">
                <div class="flex relative">
                  <img class="w-10 h-10 rounded-lg object-cover" src="../assets/user.jpg" alt="">
                  <div class="bottom-0 transform -translate-x-2 absolute bg-gray-800 text-white rounded w-6 h-6 flex justify-center items-center">
                    <svg class="" xmlns="http://www.w3.org/2000/svg" width="14" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                  </div>
                  <div class="ml-4">
                    <h3 class="text-gray-900 font-semibold">Sönmez reis</h3>
                    <p class="text-gray-400">6h ago</p>
                  </div>
                </div>
                <button class="text-purple-400 text-sm bg-pink-100 border border-pink-200 h-7 w-24 rounded-lg">Accounting</button>
              </div>
              <p class="mt-5">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quam totam ipsum praesentium in? Sit, libero sunt? Odio ab nostrum saepe accusamus nulla eveniet et natus deserunt. Quasi error exercitationem iure?</p>
              <div class="flex justify-between items-center">
                <div class="flex">
                  <a class="mr-2 h-8 w-8 flex justify-center items-center bg-gray-200 rounded-lg" href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                      <path d="M5 4a2 2 0 012-2h6a2 2 0 012 2v14l-5-2.5L5 18V4z" />
                    </svg>
                  </a>
                  <a  class="flex px-3 justify-center items-center bg-gray-200 rounded-lg" href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
                      <path fill-rule="evenodd" d="M18 10c0 3.866-3.582 7-8 7a8.841 8.841 0 01-4.083-.98L2 17l1.338-3.123C2.493 12.767 2 11.434 2 10c0-3.866 3.582-7 8-7s8 3.134 8 7zM7 9H5v2h2V9zm8 0h-2v2h2V9zM9 9h2v2H9V9z" clip-rule="evenodd" />
                    </svg>
                    <p>Add Response</p>
                  </a>
                </div>
                <div>
                  <img class="w-10 h-10 rounded-lg object-cover border border-white" src="../assets/user.jpg" alt="">
                </div>
              </div>
              </div>
              <div class="bg-gray-100 p-8 mb-5 rounded-xl">
              <h1 class="text-4xl font-semibold pb-8">Lecture Rescheduling</h1>
              <div class="flex justify-between items-center">
                <div class="flex relative">
                  <img class="w-10 h-10 rounded-lg object-cover" src="../assets/user.jpg" alt="">
                  <div class="bottom-0 transform -translate-x-2 absolute bg-gray-800 text-white rounded w-6 h-6 flex justify-center items-center">
                    <svg class="" xmlns="http://www.w3.org/2000/svg" width="14" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                  </div>
                  <div class="ml-4">
                    <h3 class="text-gray-900 font-semibold">Sönmez reis</h3>
                    <p class="text-gray-400">6h ago</p>
                  </div>
                </div>
                <button class="text-purple-400 text-sm bg-pink-100 border border-pink-200 h-7 w-24 rounded-lg">Accounting</button>
              </div>
              <p class="mt-5">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quam totam ipsum praesentium in? Sit, libero sunt? Odio ab nostrum saepe accusamus nulla eveniet et natus deserunt. Quasi error exercitationem iure?</p>
              <div class="flex justify-between items-center">
                <div class="flex">
                  <a class="mr-2 h-8 w-8 flex justify-center items-center bg-gray-200 rounded-lg" href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                      <path d="M5 4a2 2 0 012-2h6a2 2 0 012 2v14l-5-2.5L5 18V4z" />
                    </svg>
                  </a>
                  <a  class="flex px-3 justify-center items-center bg-gray-200 rounded-lg" href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
                      <path fill-rule="evenodd" d="M18 10c0 3.866-3.582 7-8 7a8.841 8.841 0 01-4.083-.98L2 17l1.338-3.123C2.493 12.767 2 11.434 2 10c0-3.866 3.582-7 8-7s8 3.134 8 7zM7 9H5v2h2V9zm8 0h-2v2h2V9zM9 9h2v2H9V9z" clip-rule="evenodd" />
                    </svg>
                    <p>Add Response</p>
                  </a>
                </div>
                <div>
                  <img class="w-10 h-10 rounded-lg object-cover border border-white" src="../assets/user.jpg" alt="">
                </div>
              </div>
              </div>
               <div class="bg-gray-100 p-8 mb-5 rounded-xl">
              <h1 class="text-4xl font-semibold pb-8">Lecture Rescheduling</h1>
              <div class="flex justify-between items-center">
                <div class="flex relative">
                  <img class="w-10 h-10 rounded-lg object-cover" src="../assets/user.jpg" alt="">
                  <div class="bottom-0 transform -translate-x-2 absolute bg-gray-800 text-white rounded w-6 h-6 flex justify-center items-center">
                    <svg class="" xmlns="http://www.w3.org/2000/svg" width="14" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                  </div>
                  <div class="ml-4">
                    <h3 class="text-gray-900 font-semibold">Sönmez reis</h3>
                    <p class="text-gray-400">6h ago</p>
                  </div>
                </div>
                <button class="text-purple-400 text-sm bg-pink-100 border border-pink-200 h-7 w-24 rounded-lg">Accounting</button>
              </div>
              <p class="mt-5">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quam totam ipsum praesentium in? Sit, libero sunt? Odio ab nostrum saepe accusamus nulla eveniet et natus deserunt. Quasi error exercitationem iure?</p>
              <div class="flex justify-between items-center">
                <div class="flex">
                  <a class="mr-2 h-8 w-8 flex justify-center items-center bg-gray-200 rounded-lg" href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                      <path d="M5 4a2 2 0 012-2h6a2 2 0 012 2v14l-5-2.5L5 18V4z" />
                    </svg>
                  </a>
                  <a  class="flex px-3 justify-center items-center bg-gray-200 rounded-lg" href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
                      <path fill-rule="evenodd" d="M18 10c0 3.866-3.582 7-8 7a8.841 8.841 0 01-4.083-.98L2 17l1.338-3.123C2.493 12.767 2 11.434 2 10c0-3.866 3.582-7 8-7s8 3.134 8 7zM7 9H5v2h2V9zm8 0h-2v2h2V9zM9 9h2v2H9V9z" clip-rule="evenodd" />
                    </svg>
                    <p>Add Response</p>
                  </a>
                </div>
                <div>
                  <img class="w-10 h-10 rounded-lg object-cover border border-white" src="../assets/user.jpg" alt="">
                </div>
              </div>
              </div>
              <div class="bg-gray-100 p-8 mb-5 rounded-xl">
              <h1 class="text-4xl font-semibold pb-8">Lecture Rescheduling</h1>
              <div class="flex justify-between items-center">
                <div class="flex relative">
                  <img class="w-10 h-10 rounded-lg object-cover" src="../assets/user.jpg" alt="">
                  <div class="bottom-0 transform -translate-x-2 absolute bg-gray-800 text-white rounded w-6 h-6 flex justify-center items-center">
                    <svg class="" xmlns="http://www.w3.org/2000/svg" width="14" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                  </div>
                  <div class="ml-4">
                    <h3 class="text-gray-900 font-semibold">Sönmez reis</h3>
                    <p class="text-gray-400">6h ago</p>
                  </div>
                </div>
                <button class="text-purple-400 text-sm bg-pink-100 border border-pink-200 h-7 w-24 rounded-lg">Accounting</button>
              </div>
              <p class="mt-5">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quam totam ipsum praesentium in? Sit, libero sunt? Odio ab nostrum saepe accusamus nulla eveniet et natus deserunt. Quasi error exercitationem iure?</p>
              <div class="flex justify-between items-center">
                <div class="flex">
                  <a class="mr-2 h-8 w-8 flex justify-center items-center bg-gray-200 rounded-lg" href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                      <path d="M5 4a2 2 0 012-2h6a2 2 0 012 2v14l-5-2.5L5 18V4z" />
                    </svg>
                  </a>
                  <a  class="flex px-3 justify-center items-center bg-gray-200 rounded-lg" href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
                      <path fill-rule="evenodd" d="M18 10c0 3.866-3.582 7-8 7a8.841 8.841 0 01-4.083-.98L2 17l1.338-3.123C2.493 12.767 2 11.434 2 10c0-3.866 3.582-7 8-7s8 3.134 8 7zM7 9H5v2h2V9zm8 0h-2v2h2V9zM9 9h2v2H9V9z" clip-rule="evenodd" />
                    </svg>
                    <p>Add Response</p>
                  </a>
                </div>
                <div>
                  <img class="w-10 h-10 rounded-lg object-cover border border-white" src="../assets/user.jpg" alt="">
                </div>
              </div>
              </div>
               <div class="bg-gray-100 p-8 mb-5 rounded-xl">
              <h1 class="text-4xl font-semibold pb-8">Lecture Rescheduling</h1>
              <div class="flex justify-between items-center">
                <div class="flex relative">
                  <img class="w-10 h-10 rounded-lg object-cover" src="../assets/user.jpg" alt="">
                  <div class="bottom-0 transform -translate-x-2 absolute bg-gray-800 text-white rounded w-6 h-6 flex justify-center items-center">
                    <svg class="" xmlns="http://www.w3.org/2000/svg" width="14" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                  </div>
                  <div class="ml-4">
                    <h3 class="text-gray-900 font-semibold">Sönmez reis</h3>
                    <p class="text-gray-400">6h ago</p>
                  </div>
                </div>
                <button class="text-purple-400 text-sm bg-pink-100 border border-pink-200 h-7 w-24 rounded-lg">Accounting</button>
              </div>
              <p class="mt-5">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quam totam ipsum praesentium in? Sit, libero sunt? Odio ab nostrum saepe accusamus nulla eveniet et natus deserunt. Quasi error exercitationem iure?</p>
              <div class="flex justify-between items-center">
                <div class="flex">
                  <a class="mr-2 h-8 w-8 flex justify-center items-center bg-gray-200 rounded-lg" href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                      <path d="M5 4a2 2 0 012-2h6a2 2 0 012 2v14l-5-2.5L5 18V4z" />
                    </svg>
                  </a>
                  <a  class="flex px-3 justify-center items-center bg-gray-200 rounded-lg" href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
                      <path fill-rule="evenodd" d="M18 10c0 3.866-3.582 7-8 7a8.841 8.841 0 01-4.083-.98L2 17l1.338-3.123C2.493 12.767 2 11.434 2 10c0-3.866 3.582-7 8-7s8 3.134 8 7zM7 9H5v2h2V9zm8 0h-2v2h2V9zM9 9h2v2H9V9z" clip-rule="evenodd" />
                    </svg>
                    <p>Add Response</p>
                  </a>
                </div>
                <div>
                  <img class="w-10 h-10 rounded-lg object-cover border border-white" src="../assets/user.jpg" alt="">
                </div>
              </div>
              </div>
              <div class="bg-gray-100 p-8 mb-5 rounded-xl">
              <h1 class="text-4xl font-semibold pb-8">Lecture Rescheduling</h1>
              <div class="flex justify-between items-center">
                <div class="flex relative">
                  <img class="w-10 h-10 rounded-lg object-cover" src="../assets/user.jpg" alt="">
                  <div class="bottom-0 transform -translate-x-2 absolute bg-gray-800 text-white rounded w-6 h-6 flex justify-center items-center">
                    <svg class="" xmlns="http://www.w3.org/2000/svg" width="14" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                  </div>
                  <div class="ml-4">
                    <h3 class="text-gray-900 font-semibold">Sönmez reis</h3>
                    <p class="text-gray-400">6h ago</p>
                  </div>
                </div>
                <button class="text-purple-400 text-sm bg-pink-100 border border-pink-200 h-7 w-24 rounded-lg">Accounting</button>
              </div>
              <p class="mt-5">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quam totam ipsum praesentium in? Sit, libero sunt? Odio ab nostrum saepe accusamus nulla eveniet et natus deserunt. Quasi error exercitationem iure?</p>
              <div class="flex justify-between items-center">
                <div class="flex">
                  <a class="mr-2 h-8 w-8 flex justify-center items-center bg-gray-200 rounded-lg" href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                      <path d="M5 4a2 2 0 012-2h6a2 2 0 012 2v14l-5-2.5L5 18V4z" />
                    </svg>
                  </a>
                  <a  class="flex px-3 justify-center items-center bg-gray-200 rounded-lg" href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-2" viewBox="0 0 20 20" fill="currentColor">
                      <path fill-rule="evenodd" d="M18 10c0 3.866-3.582 7-8 7a8.841 8.841 0 01-4.083-.98L2 17l1.338-3.123C2.493 12.767 2 11.434 2 10c0-3.866 3.582-7 8-7s8 3.134 8 7zM7 9H5v2h2V9zm8 0h-2v2h2V9zM9 9h2v2H9V9z" clip-rule="evenodd" />
                    </svg>
                    <p>Add Response</p>
                  </a>
                </div>
                <div>
                  <img class="w-10 h-10 rounded-lg object-cover border border-white" src="../assets/user.jpg" alt="">
                </div>
              </div>
              </div>
            </div>
        </div>
      </div>
      <div
        class="bg-gray-50 pr-4 sm:pr-6 lg:pr-8 lg:flex-shrink-0 lg:border-l lg:border-gray-200 xl:pr-0"
      >
        <div class="pl-6 lg:w-80">
            <!--- Right Sidebar -->
        </div>
      </div>
    </div>
  </div>
</template>

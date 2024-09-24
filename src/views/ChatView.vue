<template>
  <div class="grid grid-flow-row bg-gray-800" style="height: 100vh" id="container">
    <div class="row-span-4 m-5">
      <div>
        <div class="bg-white h-auto w-2/3 rounded-xl p-2 flex flex-col">
          <p class="text-black font-semibold">some random text to get started with</p>
          <p style="margin-left: 90%" class="text-xs hover:text-blue-500 material-icons">
            content_copy
          </p>
        </div>
        <div class="bg-gray-700 w-2/3 rounded-xl ml-auto mt-5 text-white p-2 h-auto">
          <p>some random answer is coming in to the user to see and get some ideas to start</p>
          <p style="margin-left: 90%" class="text-xs hover:text-blue-500 material-icons">
            content_copy
          </p>
        </div>
      </div>

      <!-- second -->
      <p class="mt-5"></p>
      <!-- second -->
      <div>
        <div class="bg-white h-auto w-2/3 rounded-xl p-2 flex flex-col">
          <p class="text-black font-semibold">some random text to get started with</p>
          <p style="margin-left: 90%" class="text-xs hover:text-blue-500 material-icons">
            content_copy
          </p>
        </div>
        <div class="bg-gray-700 w-2/3 rounded-xl ml-auto mt-5 text-white p-2 h-auto">
          <p>some random answer is coming in to the user to see and get some ideas to start</p>
          <p style="margin-left: 90%" class="text-xs hover:text-blue-500 material-icons">
            content_copy
          </p>
        </div>
      </div>
    </div>
    <div class="bg-gray-700 rounded-t-3xl flex justify-center items-center">
      <div class="gap-3 bg-gray-800 rounded-full px-3 lg:w-96 py-3 flex items-center">
        <span class="material-icons text-white">attachment</span>
        <input
          type="text"
          class="bg-gray-800 outline-none"
          id="send"
          placeholder="Type something..."
        />
        <span class="material-icons text-white">mic</span>
      </div>
      <span class="material-icons text-white ml-5">send</span>
    </div>
  </div>
</template>

<script setup></script>

<style>
@media screen and (min-width: 720px) {
  #container {
    width: 100vw;
    padding: 0 10%;
  }

  #send {
    width: 70vw;
  }
}

@media screen and (min-width: 700px) {
  #input {
    width: 55vw;
  }
}
</style>

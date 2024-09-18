<script setup lang="ts"></script>

<template>
  <main>
    <div class="sm:grid sm:grid-cols-2 sm:gap-5">
      <div class="mt-5 sm:rounded-3xl" id="bot">
        <img
          src="../../public/bot.jpeg"
          alt=""
          class="rounded-full sm:h-1/5 lg:rounded-none sm:invisible"
        />
      </div>
      <div class="flex sm:my-auto flex-col gap-2 sm:ml-10 mt-5">
        <h2 class="capitalize text-3xl text-center">Your Intelligent Companion</h2>

        <p class="text-gray-400 text-center">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore in dolores quis magni
          cupiditate excepturi fugiat? Voluptatem inventore dolorum sapiente odio facilis? Alias,
          veritatis. Voluptatum magni facere quidem ad similique.
        </p>

        <div class="flex justify-center mt-5">
          <router-link
            to="/chat"
            class="bg-blue-500 text-white px-4 py-2 rounded-full font-semibold hover:bg-blue-900"
          >
            Start Chatting
          </router-link>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
#bot {
  background-image: url('../../public/bot.jpeg');
  background-position: center;
  background-size: cover;
  height: 70vh;
}
@media screen and (max-width: 640px) {
  #bot {
    height: auto;
    background-image: none;
  }
}
</style>

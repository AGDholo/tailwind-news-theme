<template>
  <div class="grid grid-cols-4 gap-4">
    <div v-for="item in 4">
      <div class="flex hover:bg-gray-100 cursor-pointer py-4">
        <img
          class="shadow-lg"
          width="80"
          height="60"
          src="https://images.pexels.com/photos/6694377/pexels-photo-6694377.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=60&w=80"
          alt="image"
        />
        <div class="justify-center flex flex-col ml-2">
          <div class="font-bold">HeroUI</div>
          <div>WEB developer</div>
        </div>
      </div>
    </div>
  </div>

  <div class="bg-gray-400" style="height: 1px"></div>
  <div class="bg-gray-400 mt-1" style="height: 1px"></div>
</template>

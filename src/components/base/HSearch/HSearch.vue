<template>
  <div class="relative">
    <input
      type="text"
      class="
        py-2
        pl-8
        rounded
        focus:bg-white
        focus:outline-none
        focus:ring-2
        focus:ring-black
        focus:border-transparent
      "
      placeholder="Search..."
      value=""
      style="width: 150px"
    />
    <svg
      class="w-6 h-6 absolute left-1.5 top-2"
      fill="none"
      stroke="currentColor"
      viewBox="0 0 24 24"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="2"
        d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
      ></path>
    </svg>
  </div>
</template>

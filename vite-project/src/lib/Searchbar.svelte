<!--
  This example requires some changes to your config:
  
  ```
  // tailwind.config.js
  module.exports = {
    // ...
    plugins: [
      // ...
      require('@tailwindcss/forms'),
    ],
  }
  ```
-->
<div>
  <div class="relative mt-1 rounded-md shadow-sm">
    <div class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-3">
      <span class="text-gray-500 md:text-md">$</span>
    </div>
    <input type="text" name="search" id="search" class="block w-full rounded-md border-gray-300 p-2 pl-7 pr-12 focus:border-indigo-500 focus:ring-indigo-500 md:text-md" placeholder="Search a book..">
  </div>
</div>

<template>
 <div class="max-w-4xl mx-auto p-6">
   <div class="bg-white dark:bg-gray-800 rounded-lg px-6 py-8 ring-1 ring-gray-900/5 shadow w-1/2 mx-auto">
  <div>
    <span class="inline-block p-2 bg-indigo-500 rounded-md shadow-lg">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-white" viewBox="0 0 20 20" fill="currentColor">
  <path d="M17.414 2.586a2 2 0 00-2.828 0L7 10.172V13h2.828l7.586-7.586a2 2 0 000-2.828z" />
  <path fill-rule="evenodd" d="M2 6a2 2 0 012-2h4a1 1 0 010 2H4v10h10v-4a1 1 0 112 0v4a2 2 0 01-2 2H4a2 2 0 01-2-2V6z" clip-rule="evenodd" />
</svg>
    </span>
  </div>
  <h3 class="text-gray-800 dark:text-teal-600 mt-5 text-base font-medium tracking-tight">Writes Upside-Down</h3>
  <p class="text-gray-500 dark:text-gray-300 mt-2 text-sm">
    The Zero Gravity Pen can be used to write in any orientation, including upside-down. It even works in outer space.
  </p>
  
</div>
 </div>
</template>

<script>
export default {
  name: 'index',
  mounted() {
    const htm  = document.querySelector('html');
  //  console.log(htm.classList.add(('dark bg-black')))
  htm.classList.add('dark' , 'bg-noir')
  console.log(htm)
  }
 
}
</script>
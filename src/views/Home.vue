<template>    
  <div class="home flex justify-center flex-col items-center">
      <h1 class="text-5xl">Welcome</h1>
      <img class="hidden lg:block w-full h-64 object-cover" src="https://source.unsplash.com/random" alt="">
      <div class="flex flex-col -m-24 items-center bg-gray-400 w-1/3 p-10 rounded-lg shadow-xl">
          <img class="h-64 w-64 rounded-full object-cover" src="https://source.unsplash.com/random" alt="" srcset="">
          <h5 class="text-2xl font-semibold">Some Image Information</h5>
          <p class="text-left mt-4 ">
              <span class="text-purple-700 font-extrabold">Lorem ipsum</span> dolor sit, amet consectetur adipisicing elit. Dicta architecto dolorum tempore 
              sunt exercitationem saepe totam dolores enim accusamus. Corporis animi soluta, 
              rerum autem non nulla adipisci laboriosam ex cum!
        </p>
      </div>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    //HelloWorld
  }
}
</script>

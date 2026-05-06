<script>
  import besique from '$lib/assets/besique.jpg';
  import dana from '$lib/assets/dana.jpg';
  import elvis from '$lib/assets/elvis.jpg';
  import james from '$lib/assets/james.jpg';
</script>

<div class="min-h-screen bg-gray-100 flex justify-center items-center p-10">

  <div class="bg-white w-full max-w-5xl rounded-2xl shadow-lg p-6">

    <div class="flex justify-between items-center mb-6">

      <div>
        <h1 class="text-2xl font-bold text-gray-800"> User Accounts </h1>
<p class="text-sm text-gray-500"> View accounts of registered users  </p>
      </div>

      <button class="bg-blue-600 hover:bg-blue-700 text-white px-5 py-2 rounded-lg text-sm font-medium">  ↓ CSV </button>

    </div>

    
    <div class="rounded-xl overflow-hidden border border-gray-200">

      
      <div class="grid grid-cols-[58px_1.5fr_1fr_1fr_1fr] bg-blue-600 text-white text-sm font-semibold p-4">
        <div>ID</div>
        <div>FULL NAME</div>
        <div>USER ROLE</div>
        <div>CREATED AT</div>
        <div>STATUS</div>
      </div>

      
      <div class="grid grid-cols-[58px_1.5fr_1fr_1fr_1fr] items-center p-3 border-t border-gray-100">

        <div class="text-sm">3</div>

        <div class="flex items-center gap-3">
          <img src={besique} class="w-10 h-10 rounded-full object-cover" alt="">
          <span>Besique Monroe</span>
        </div>

        <div class="text-gray-600">Administrator</div>

        <div class="text-gray-500">Sep 28, 2022</div>

        <div>
          <span class="bg-green-100 text-green-700 px-3 py-1 rounded-full text-sm font-semibold"> Active</span>
        </div>

      </div>

      
      <div class="grid grid-cols-[58px_1.5fr_1fr_1fr_1fr] items-center p-3 border-t border-gray-100">

        <div class="text-sm">7</div>

        <div class="flex items-center gap-3">
          <img src={james} class="w-10 h-10 rounded-full object-cover" alt="">
          <span>James Cavier</span>
        </div>

        <div class="text-gray-600">Author</div>

        <div class="text-gray-500">Sep 28, 2022</div>

        <div>
          <span class="bg-green-100 text-green-700 px-3 py-1 rounded-full text-sm font-semibold">Active</span>
        </div>

      </div>

    
      <div class="grid grid-cols-[58px_1.5fr_1fr_1fr_1fr] items-center p-3 border-t border-gray-100">

        <div class="text-sm">12</div>

        <div class="flex items-center gap-3">
          <img src={elvis} class="w-10 h-10 rounded-full object-cover" alt="">
          <span>Elvis Son</span>
        </div>

        <div class="text-gray-600">Editor</div>

        <div class="text-gray-500">Sep 28, 2022</div>

        <div>
          <span class="bg-yellow-100 text-yellow-700 px-3 py-1 rounded-full text-sm font-semibold">Suspended</span>
        </div>

      </div>

     
      <div class="grid grid-cols-[58px_1.5fr_1fr_1fr_1fr] items-center p-3 border-t border-gray-100">

        <div class="text-sm">66</div>

        <div class="flex items-center gap-3">
          <img src={dana} class="w-10 h-10 rounded-full object-cover" alt="">
          <span>Dana White</span>
        </div>

        <div class="text-gray-600">Administrator</div>

        <div class="text-gray-500">Sep 28, 2022</div>

        <div>
          <span class="bg-red-100 text-red-700 px-3 py-1 rounded-full text-sm font-semibold"> Inactive</span>
        </div>

      </div>

    </div>

  </div>

</div>
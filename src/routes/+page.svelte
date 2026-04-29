<script>
  import besique from '$lib/assets/besique.jpg';
  import dana from '$lib/assets/dana.jpg';
  import elvis from '$lib/assets/elvis.jpg';
  import james from '$lib/assets/james.jpg';
</script>

<div class="min-h-screen bg-gray-100 flex justify-center items-center p-10">

  <div class="bg-white w-full max-w-5xl rounded-2xl shadow-lg p-6">

    <!-- Header -->
    <div class="flex justify-between items-center mb-6">

      <div>
        <h1 class="text-2xl font-bold text-gray-800">
          User Accounts
        </h1>

        <p class="text-sm text-gray-500">
          View accounts of registered users
        </p>
      </div>

      <button class="bg-blue-600 hover:bg-blue-700 text-white px-5 py-2 rounded-lg text-sm font-medium">
        ↓ CSV
      </button>

    </div>

    <!-- Table -->
    <div class="rounded-xl overflow-hidden border border-gray-200">

      <!-- Head -->
      <div class="grid grid-cols-[58px_1.5fr_1fr_1fr_1fr] bg-blue-600 text-white text-sm font-semibold p-4">
        <div>ID</div>
        <div>FULL NAME</div>
        <div>USER ROLE</div>
        <div>CREATED AT</div>
        <div>STATUS</div>
      </div>

    </div>

  </div>

</div>
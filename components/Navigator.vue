<template>
  <!-- container -->

  <aside
    class="flex flex-col items-center text-gray-700 shadow h-full bg-blue-100 fixed top-0 left-0"
  >
    <!-- Side Nav Bar-->
    <!--
		<div class="">

			<nuxt-link to="/" class="h-16 px-6 flex justify-center items-center w-full">
				<font-awesome-icon :icon="['fas', 'home']" />
			</nuxt-link>
		</div> -->

    <ul>
      <li class="hover:bg-blue-300">
        <nuxt-link
          to="/"
          class="h-16 px-6 flex justify-center items-center w-full
					focus:text-orange-500"
        >
          <font-awesome-icon :icon="['fas', 'home']" />
        </nuxt-link>
      </li>
      <!-- Items Section -->
      <li class="hover:bg-blue-300">
        <nuxt-link
          to="/movie"
          class="h-16 px-6 flex justify-center items-center w-full
					focus:text-orange-500"
        >
          <font-awesome-icon :icon="['fas', 'film']" />
        </nuxt-link>
      </li>

      <li class="hover:bg-blue-300">
        <nuxt-link
          to="/music"
          class="h-16 px-6 flex justify-center items-center w-full
					focus:text-orange-500"
        >
          <font-awesome-icon :icon="['fas', 'music']" />
        </nuxt-link>
      </li>

      <li class="hover:bg-blue-300">
        <nuxt-link
          to="/quote"
          class="h-16 px-6 flex justify-center items-center w-full
					focus:text-purple-500"
        >
          <font-awesome-icon :icon="['fas', 'quote-right']" />
        </nuxt-link>
      </li>

      <li class="hover:bg-blue-300">
        <nuxt-link
          to="/settings"
          class="h-16 px-6 flex justify-center items-center w-full
					focus:text-purple-500"
        >
          <font-awesome-icon :icon="['fas', 'cog']" />
        </nuxt-link>
      </li>
      <!--
			<li class="hover:bg-gray-100">
				<a
					href="."
					class="h-16 px-6 flex flex justify-center items-center w-full
					focus:text-orange-500">
					<svg
						class="h-5 w-5"
						xmlns="http://www.w3.org/2000/svg"
						width="24"
						height="24"
						viewBox="0 0 24 24"
						fill="none"
						stroke="currentColor"
						stroke-width="2"
						stroke-linecap="round"
						stroke-linejoin="round">
						<circle cx="12" cy="12" r="3"></circle>
						<path
							d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1
							0 2.83 2 2 0 0 1-2.83 0l-.06-.06a1.65 1.65 0 0
							0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-2 2 2
							2 0 0 1-2-2v-.09A1.65 1.65 0 0 0 9 19.4a1.65 1.65 0 0
							0-1.82.33l-.06.06a2 2 0 0 1-2.83 0 2 2 0 0 1
							0-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0
							0-1.51-1H3a2 2 0 0 1-2-2 2 2 0 0 1 2-2h.09A1.65 1.65
							0 0 0 4.6 9a1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0
							1 0-2.83 2 2 0 0 1 2.83 0l.06.06a1.65 1.65 0 0 0
							1.82.33H9a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 2-2 2 2
							0 0 1 2 2v.09a1.65 1.65 0 0 0 1 1.51 1.65 1.65 0 0 0
							1.82-.33l.06-.06a2 2 0 0 1 2.83 0 2 2 0 0 1 0
							2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82V9a1.65 1.65 0 0
							0 1.51 1H21a2 2 0 0 1 2 2 2 2 0 0 1-2 2h-.09a1.65
							1.65 0 0 0-1.51 1z"></path>
					</svg>
				</a>
			</li>

			<li class="hover:bg-gray-100">
				<a
					href="."
					class="h-16 px-6 flex flex justify-center items-center w-full
					focus:text-orange-500">
					<svg
						class="h-5 w-5"
						xmlns="http://www.w3.org/2000/svg"
						width="24"
						height="24"
						viewBox="0 0 24 24"
						fill="none"
						stroke="currentColor"
						stroke-width="2"
						stroke-linecap="round"
						stroke-linejoin="round">
						<path
							d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9"></path>
						<path d="M13.73 21a2 2 0 0 1-3.46 0"></path>
					</svg>
				</a>
			</li> -->
    </ul>

    <div class="mt-auto h-16 flex items-center w-full">
      <!-- Action Section -->
      <button
        class="h-16 w-10 mx-auto flex justify-center items-center
				w-full focus:text-orange-500 hover:bg-red-200 focus:outline-none"
      >
        <svg
          class="h-5 w-5 text-red-700"
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path d="M9 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h4"></path>
          <polyline points="16 17 21 12 16 7"></polyline>
          <line x1="21" y1="12" x2="9" y2="12"></line>
        </svg>
      </button>
    </div>
  </aside>
</template>
<script>
export default {
  data() {
    return {
      isMenuOpen: false
    };
  }
};
</script>
<style scoped>
.nuxt-link-exact-active {
  background-color: #4fc3f7;
  color: white;
}
</style>

<template>
  <div class="w-full border border-gray-100">
    <div
      class="
        h-full
        overflow-hidden
         group
            hover:shadow-2xl
        duration-150
        
      "
    >
      <div
        class="aspect-w-9
        aspect-h-12"
      >
        <img class=" w-full object-cover" :src="movie.poster" alt="blog" />
      </div>      <div class="p-6">
        <h1 class="title-font text-lg font-medium text-gray-900">
          {{ movie.name }}
        </h1>
        <div class="flex">
          <h2
            v-for="(cat, index) in movie.categories"
            :key="index"
            class="
              tracking-widest
              text-xs
              title-font
              font-medium
              text-gray-400
              mb-1
            "
          >
            <span v-if="index === movie.categories.length - 1">{{
              cat.title
            }}</span>
            <span v-else>{{ cat.title + ", " }}</span>
          </h2>
        </div>
        <blockquote class="my-2 font-serif italic">
          {{ '" ' + movie.quote + '"' }}
        </blockquote>
        <div class="flex items-center justify-between flex-wrap">
          <a class="text-blue-500 inline-flex items-center md:mb-2 lg:mb-0"
            >Chi tiết
            <svg
              class="w-4 h-4 ml-2"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path d="M5 12h14"></path>
              <path d="M12 5l7 7-7 7"></path>
            </svg>
          </a>
          <span
            class="text-gray-400 inline-flex items-center leading-none text-sm"
          >
            <font-awesome-icon :icon="['far', 'star']" class="mr-1" />
            {{ movie.rates }}
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    movie: {
      type: Object,
      required: true,
      default: {}
    }
  }
};
</script>

<style lang="scss" scoped></style>

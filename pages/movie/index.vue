<template>
  <div class="relative">
    <div class="relative px-11 mt-3 flex justify-between items-center z-50">
      <Search />
      <div><Settings /></div>
    </div>
    <div class="relative grid grid-cols-3 w-full px-11 gap-8 mt-16 z-50">
      <div v-for="(movie, index) in movies" :key="index">
        <MovieBox :movie="movie" />
      </div>
    </div>
    <div
      class="
        fixed
        items-center
        justify-center
        overflow-hidden
        flex
        left-0
        top-0
        w-full
        h-full
        z-0
      "
    >
      <svg viewBox="0 0 88 88" class="w-full max-w-screen-xl text-blue-200">
        <circle fill="currentColor" cx="44" cy="44" r="15.5"></circle>
        <circle
          fill-opacity="0.2"
          fill="currentColor"
          cx="44"
          cy="44"
          r="44"
        ></circle>
        <circle
          fill-opacity="0.2"
          fill="currentColor"
          cx="44"
          cy="44"
          r="37.5"
        ></circle>
        <circle
          fill-opacity="0.3"
          fill="currentColor"
          cx="44"
          cy="44"
          r="29.5"
        ></circle>
        <circle
          fill-opacity="0.3"
          fill="currentColor"
          cx="44"
          cy="44"
          r="22.5"
        ></circle>
      </svg>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      movies: [
        {
          name: "Ruby sparks",
          poster: "/img/rubyspark.jpg",
          quote:
            "I couldn't see you when you were here and, now that you're gone, I see you everywhere.",
          director: ["Jonathan Dayton", "Valerie Faris"],
          actor: [],
          rates: 4,
          link: [
            {
              title: "Spiderum",
              to: "https://spiderum.com/bai-dang/RUBY-SPARKS-KHONG-AI-HOAN-HAO-tang-chi-Sieu-89g",
            },
          ],
          categories: [
            {
              title: "Comedy",
            },
            {
              title: "Drama",
            },
          ],
        },
        {
          name: "Ruby sparks",
          poster: "/img/rubyspark.jpg",
          quote:
            "I couldn't see you when you were here and, now that you're gone, I see you everywhere.",
          director: ["Jonathan Dayton", "Valerie Faris"],
          actor: [],
          rates: 4,
          link: [
            {
              title: "Spiderum",
              to: "https://spiderum.com/bai-dang/RUBY-SPARKS-KHONG-AI-HOAN-HAO-tang-chi-Sieu-89g",
            },
          ],
          categories: [
            {
              title: "Comedy",
            },
            {
              title: "Drama",
            },
          ],
        },
        {
          name: "Ruby sparks",
          poster: "/img/rubyspark.jpg",
          quote:
            "I couldn't see you when you were here and, now that you're gone, I see you everywhere.",
          director: ["Jonathan Dayton", "Valerie Faris"],
          actor: [],
          rates: 4,
          link: [
            {
              title: "Spiderum",
              to: "https://spiderum.com/bai-dang/RUBY-SPARKS-KHONG-AI-HOAN-HAO-tang-chi-Sieu-89g",
            },
          ],
          categories: [
            {
              title: "Comedy",
            },
            {
              title: "Drama",
            },
          ],
        },
        {
          name: "Ruby sparks",
          poster: "/img/rubyspark.jpg",
          quote:
            "I couldn't see you when you were here and, now that you're gone, I see you everywhere.",
          director: ["Jonathan Dayton", "Valerie Faris"],
          actor: [],
          rates: 4,
          link: [
            {
              title: "Spiderum",
              to: "https://spiderum.com/bai-dang/RUBY-SPARKS-KHONG-AI-HOAN-HAO-tang-chi-Sieu-89g",
            },
          ],
          categories: [
            {
              title: "Comedy",
            },
            {
              title: "Drama",
            },
          ],
        },
        {
          name: "Ruby sparks",
          poster: "/img/rubyspark.jpg",
          quote:
            "I couldn't see you when you were here and, now that you're gone, I see you everywhere.",
          director: ["Jonathan Dayton", "Valerie Faris"],
          actor: [],
          rates: 4,
          link: [
            {
              title: "Spiderum",
              to: "https://spiderum.com/bai-dang/RUBY-SPARKS-KHONG-AI-HOAN-HAO-tang-chi-Sieu-89g",
            },
          ],
          categories: [
            {
              title: "Comedy",
            },
            {
              title: "Drama",
            },
          ],
        },
        {
          name: "Ruby sparks",
          poster: "/img/rubyspark.jpg",
          quote:
            "I couldn't see you when you were here and, now that you're gone, I see you everywhere.",
          director: ["Jonathan Dayton", "Valerie Faris"],
          actor: [],
          rates: 4,
          link: [
            {
              title: "Spiderum",
              to: "https://spiderum.com/bai-dang/RUBY-SPARKS-KHONG-AI-HOAN-HAO-tang-chi-Sieu-89g",
            },
          ],
          categories: [
            {
              title: "Comedy",
            },
            {
              title: "Drama",
            },
          ],
        },
        {
          name: "Ruby sparks",
          poster: "/img/rubyspark.jpg",
          quote:
            "I couldn't see you when you were here and, now that you're gone, I see you everywhere.",
          director: ["Jonathan Dayton", "Valerie Faris"],
          actor: [],
          rates: 4,
          link: [
            {
              title: "Spiderum",
              to: "https://spiderum.com/bai-dang/RUBY-SPARKS-KHONG-AI-HOAN-HAO-tang-chi-Sieu-89g",
            },
          ],
          categories: [
            {
              title: "Comedy",
            },
            {
              title: "Drama",
            },
          ],
        },
      ],
    };
  },
};
</script>

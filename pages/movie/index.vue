<template>
  <div>
    <div class="px-11 mt-3 flex justify-between items-center">
        <Search />
        <div><Settings /></div>
    </div>
    <div class="grid grid-cols-3 w-full px-11 gap-8 mt-16">
      <div v-for="(movie, index) in movies" :key="index">
        <MovieBox :movie="movie" />
      </div>
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
              to:
                "https://spiderum.com/bai-dang/RUBY-SPARKS-KHONG-AI-HOAN-HAO-tang-chi-Sieu-89g"
            }
          ],
          categories: [
            {
              title: "Comedy"
            },
            {
              title: "Drama"
            }
          ]
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
              to:
                "https://spiderum.com/bai-dang/RUBY-SPARKS-KHONG-AI-HOAN-HAO-tang-chi-Sieu-89g"
            }
          ],
          categories: [
            {
              title: "Comedy"
            },
            {
              title: "Drama"
            }
          ]
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
              to:
                "https://spiderum.com/bai-dang/RUBY-SPARKS-KHONG-AI-HOAN-HAO-tang-chi-Sieu-89g"
            }
          ],
          categories: [
            {
              title: "Comedy"
            },
            {
              title: "Drama"
            }
          ]
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
              to:
                "https://spiderum.com/bai-dang/RUBY-SPARKS-KHONG-AI-HOAN-HAO-tang-chi-Sieu-89g"
            }
          ],
          categories: [
            {
              title: "Comedy"
            },
            {
              title: "Drama"
            }
          ]
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
              to:
                "https://spiderum.com/bai-dang/RUBY-SPARKS-KHONG-AI-HOAN-HAO-tang-chi-Sieu-89g"
            }
          ],
          categories: [
            {
              title: "Comedy"
            },
            {
              title: "Drama"
            }
          ]
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
              to:
                "https://spiderum.com/bai-dang/RUBY-SPARKS-KHONG-AI-HOAN-HAO-tang-chi-Sieu-89g"
            }
          ],
          categories: [
            {
              title: "Comedy"
            },
            {
              title: "Drama"
            }
          ]
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
              to:
                "https://spiderum.com/bai-dang/RUBY-SPARKS-KHONG-AI-HOAN-HAO-tang-chi-Sieu-89g"
            }
          ],
          categories: [
            {
              title: "Comedy"
            },
            {
              title: "Drama"
            }
          ]
        }
      ]
    };
  }
};
</script>

<template>
  <div id="article">

    <div v-for="article in articles" :key="article.id">

      <div class="row articles">

        <div class="col-md-8">

          <h2>{{ article.name }}</h2>

          <p class="paragraph">{{ article.content }}</p>

        </div>

        <div class="col-md-4">

          <img :src="article.picture" alt="" />
          <div class="author mt-3">
              <p>Author: {{ article.author }}</p>
              <p>{{ article.year }}</p>
          </div>
          

        </div>

      </div>

    </div>

  </div>
</template>

<script>
import Articles from "../assets/data/articles.json";

export default {
  name: "Article",
  data() {
    return {
      articles: Articles,
    };
  },
};
</script>

<style scoped>

.paragraph {
  text-align: justify;
  font-weight: 100;
  margin-top: 2rem;
  font-weight: 300;
  
}

.author p {
    font-size: 1rem;
    text-align: center;
}

.articles {
  font-size: 1.3rem;
  background: rgb(250, 250, 250);
  padding: 2rem;
  margin-bottom: 3rem;
}

img {
    border-radius: 50%;
    width: 200px;
}

</style>
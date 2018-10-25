<template>
  <div class="conteiner-block">
      <article class="block-article">
          <h1 class="heading-article">
            Cryptozen - криптовалютный майнинговый фона , созданный для уменьшения рисков , позволяющий даже людей без обширных знаний в этой области получать большую прибыль , размер которой очень редок в обычных областях инвестирования .
          </h1>
          <p class="article-text">
              It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to 
          </p>
      </article>
      <div class="block-article_blog">
        <div class="article-text_blog">
            <div class="logo-article">
                <img class="logo-article_blog" src="../assets/img.jpg" >
            </div>
            <article>
                <h3 class="heading-article_blog">
                  СВЕРХПРИБЫЛИ
                </h3>
                <p class="article-text">
                is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. 
                </p>
            </article>   
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'HomeContent',
  props: {
    massege: String,
  },
};
</script>

<style scoped lang="scss">
.heading-article {
  font-size: 10px;
  font: bold;
}
</style>

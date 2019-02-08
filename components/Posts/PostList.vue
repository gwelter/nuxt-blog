<template>
  <section class="featured-posts">
    <PostPreview
      :id="1"
      title="Post 1"
      previewText="Post 1 néeahhh"
      :thumbnail="'https://i2-prod.manchestereveningnews.co.uk/incoming/article14379834.ece/ALTERNATES/s615/050318_LRR_MEN_WomenTech.jpg'" />
    <PostPreview
      :id="2"
      :title="'Post 2'"
      :previewText="'Post 2 néeahhh'"
      :thumbnail="'https://i2-prod.manchestereveningnews.co.uk/incoming/article14379834.ece/ALTERNATES/s615/050318_LRR_MEN_WomenTech.jpg'" />
  </section>
</template>

<script>
import PostPreview from '~/components/Posts/PostPreview'

export default {
  components: { PostPreview }
}
</script>

<style scoped>
.featured-posts {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>

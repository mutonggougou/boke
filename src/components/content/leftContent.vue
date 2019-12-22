<template>
<div class="left-Content">
  <ArticleList/>
  <ArticleList/>
  <ArticleList/>
  <ArticleList/>
  <ArticleList/>
  <ArticleList/>
</div>

</template>

<script>
import ArticleList from '../header/articleList.vue';
export default {
  name: 'LeftContent',
   components: { 
     ArticleList
   }                                    
};
</script>

<style>
.left-Content {
  width: 804px;
    height: 800px;
    padding-right: 50px;
    padding-top: 20px;
    float: left;

}
</style>

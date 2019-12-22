<template>
  <div class="blog">
     <Header /> 
    <!-- <div class="Content">
        <div class="left-container">左侧内容</div>
        <div class="right-container">
        右侧内容</div>
    </div> --> <Content/> 
   <Footer/>
   </div>
</template>

<script>

 import Header from '../components/header/index.vue';
 import Content from '../components/content/index.vue';
 import Footer from '../components/footer.vue';

export default {
  name: 'Container',
  components: {  
  Header,
   Content, 
   Footer
  }             
};
</script>

<style>
.blog{
  padding: 0 60px;
    max-width: 1150px;
    margin: 0 auto;
}

</style>

<template>
 <header>
    <Bloginfo/>
     <Navigation/>
 </header>
</template>

<script>
import Bloginfo from './bloginfo.vue';
import Navigation from './navigation.vue';
export default {
  name: 'Header',
   components: { 
       Bloginfo,
       Navigation
   }                                    
};
</script>

<style>
header {
    padding: 58px 0 0;
    text-align: left;
    border-bottom: 1px solid #ddd;
    position: relative;
}
</style>

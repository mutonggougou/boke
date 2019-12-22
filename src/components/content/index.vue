<template>
 <div class="content">
     <LeftContent/>
     <RightContent/>
 </div>
</template>

<script>
import LeftContent from './leftContent.vue';
import RightContent from './rightContent.vue';

export default {
  name: 'Content',
   components: { 
     LeftContent,
     RightContent  
   }                                    
};
</script>

<style>
.content{
  width:100%;
  overflow: hidden;
}
</style>

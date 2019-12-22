<template>
 <div class="bloginfo">
   <div class="blogname">{{blogTitle}} </div>
   <div class="blogDes">{{blogdes}} </div>
   <!-- <bloginfo/> -->
 </div>
</template>
<script>
import bloginfo from "../../../mock/bloginfo.js";
  //window.console.log(Object.assign ({},bloginfo));
export default {
  name: 'Bloginfo',
  components: {},
   data() {
     return Object.assign ({},bloginfo);
    //我们这边有一个方法叫Object.assign 合并数据先写个空对象 再把数据合并进来,对象合并如下：{test:a},bloginfo = {test:a,blogTItle:'11',blogDes:'22'} 即生成了一个新的对象
   },           
}
</script>

<style>
.blogname{
  font: bold 25px/1.12 "Times New Roman", Georgia, Times, sans-serif;
    color: #555;
}
.blogDes{
  font-size: 12px;
    color: #999;
}
</style>

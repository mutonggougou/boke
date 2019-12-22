<template>
<nav>
    <a href="#" v-for="item in nav" :key="item.id" :to="item.title" >{{item.name}}</a>
   
 </nav>
</template>
<script>
import navigation from '../../../mock/navigation .js';
  window.console.log(Object.assign({},navigation))
 // v-for="item in items"是指令也就是封装的意思，用列表渲染的指令实现众多代码简化后的渲染

export default {
  name: 'Navigation',
  components: {},
   data() {
       return Object.assign({},navigation);
   },             
};
</script>

<style>
nav {
    margin: 10px 0 -1px;
    padding: 0;
    position: absolute;
    right: 0;
    bottom: 0;
}
 nav a {
    display: inline-block;
    padding: 3px 20px 3px;
    line-height: 30px;
    color: #444;
    font-size: 11px;
}
nav a.current {
    border: 1px solid #ddd;
    border-bottom-color: #fff;
}

</style>

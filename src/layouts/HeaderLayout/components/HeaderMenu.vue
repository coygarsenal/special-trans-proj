<template>
  <div class="header_menu ml-[90px]">
    <ul class="menu flex text-dark ">
      <li class="mr-14 hover:text-brand cursor-pointer duration-300" v-for="item in menuItems" :key="item"> 
        {{ item.name }}
      </li>
    </ul>
  </div>
</template>

<script>
import menuList from './meniList';


  export default {
    data(){
      return {
        menuItems: menuList
      }
    }
  }
</script>
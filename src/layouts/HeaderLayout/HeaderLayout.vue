<template>
  <header class="header fixed top-0 w-full">
    <div class="container items-center flex">
      <HeaderLogo />
     <HeaderMenu />
      <HeaderActions />
    </div>
  </header>
</template>

<script>
import HeaderActions from './components/Header.Actions.vue';
import HeaderLogo from './components/HeaderLogo.vue';
import HeaderMenu from './components/HeaderMenu.vue';

  export default{
    components: { HeaderLogo, HeaderMenu, HeaderActions }
}
</script>
<template>
  <div class="home-page">
    <h1>Hello World</h1>
    <TheButton> Заказать звонок</TheButton>
    <TheTitle>Hello world</TheTitle>
  </div>
</template>

<script>
import TheButton from '../../ui/TheButton.vue';
import TheTitle from '../../ui/TheTitle.vue';

export default {
    components: { TheButton, TheTitle}
}
</script>
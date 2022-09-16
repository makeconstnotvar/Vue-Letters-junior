<template>
  <main>
    <h1>Буквы</h1>
    <div>{{ letters }}</div>
    <h2>Пары букв</h2>
    <div>Тут выводим пары букв</div>
  </main>
</template>
<script>
/*
1 Сформировать массив из пар ['AA','AB',...'AZ','BA','BB'...'ZZ'].
2 Вывести все пары на страницу.
3 Сделать рядом с каждой парой кнопку, которая красит пару в зеленый цвет.
4 Сделать рядом с каждой парой еще одну кнопку, которая удалит эту пару со страницы.
*/
export default {
  name: 'App',
  data() {
    return {
      letters: 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'
    }
  },
  created() {
    console.log('Привет')
  }
}
</script>
<style>

</style>

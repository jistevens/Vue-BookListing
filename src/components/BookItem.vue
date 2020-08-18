<template>
<li>{{ book.title }}: {{ book.author }}</li>
</template>

<style>
li {
  display: block;
  margin: 0 10px;
}
</style>

<script>
export default {
  name: 'BookItem',
  props: ['book'],
}
</script>

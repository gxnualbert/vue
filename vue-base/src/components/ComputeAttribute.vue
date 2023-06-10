<template>
    <p>Has published books:</p>
    <span>{{ author.books.length > 0 ? 'Yes' : 'No' }}</span>
    <br>
    是用compute计算后
    <span>{{ publishedBooksMessage ? 'Yes' : 'No' }}</span>

</template>

<script>
export default {
    data() {
        return {
            author: {
                name: 'John Doe',
                books: [
                    'Vue 2 - Advanced Guide',
                    'Vue 3 - Basic Guide',
                    'Vue 4 - The Mystery'
                ]
            }
        }
    },
    computed: {
    // 一个计算属性的 getter
    publishedBooksMessage() {
      // `this` 指向当前组件实例
      return this.author.books.length > 0 ? 'Yes' : 'No'
    }
  }
}
</script>
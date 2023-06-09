<template>

    <h3>模板语法</h3>
    
    <p>{{ msg }}</p>
    <p>{{ hello }}</p>
    <p>{{ number }}</p> 
    <p>{{ ok? 'Yes':'No' }}</p> 
    <p>{{ number + 1 }}</p>
    <p>{{message.split('').reverse().join('')}}</p>
    <p>{{rawHtml}}</p>
    <p v-html="rawHtml"></p>
    </template>
    
    <script>
    
    export default {
    
      data() {
        return {
          msg: 'Welcome to Your Vue.js App',
          hello: 'Hello Vue!',
          number:10,
          ok:true,
          message:'大家好，我是小明，我今年10岁了',
          rawHtml:'<span style="color:red">This should be red.</span>'  
        }
      }
    }
    
    </script>
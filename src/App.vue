<script setup>
import {ref} from 'vue'

const name = ref('')

</script>

<template>
  
  <main class="app">

    <section class="greeting">
      <h2 class="title">
        Welcome back, <input type="text" placeholder="Enter name" v-model="name">
      </h2>
    </section>

    <section class="create">


    </section>

    <section class="todo-list">

    </section>


  </main>

</template>

<template>
  <div id="app">
    <nav class="navbar is-light" role="navigation" aria-label="main navigation">
      <div class="container">
        <div class="navbar-brand">
          <a class="navbar-item" href="#">
            <span class="title is-size-1">NoteTaker</span>
          </a>
        </div>

      </div>
    </nav>
    <br><br>
    <div  class="container">
      <NoteList />
    </div>
  </div>
</template>

<script>
import NoteList from './components/NoteList.vue'

export default {
  name: 'app',
  components: {
    NoteList
  }
}
</script>

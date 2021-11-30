<template>
  <div class="board">
     <Tiptap :options="options"></Tiptap>
  </div>
</template>

<script>
import Tiptap from '../components/Tiptap.vue'
export default {
    components: {
        Tiptap
    },
    data () {
        return {
            options: {
                content: 'default text',
                editable: true
            }
        }
    }
}
</script>

<style>

</style>
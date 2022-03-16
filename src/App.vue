<template>
  <div id="app">
    <current-time class="col-4"/>
    <task-input class="col-6"/>
  </div>
</template>

<script>
import CurrentTime from "@/components/CurrentTime";
import TaskInput from "@/components/TaskInput";
export default {
  name: 'app',
  components: {TaskInput, CurrentTime},
}
</script>


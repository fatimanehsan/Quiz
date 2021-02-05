<template>
  <div>
    <b-nav tabs>
      <b-nav-item disabled><b> Quiz App</b></b-nav-item>
      <b-nav-item disabled>Counter: {{ numCorrect }}/{{ numTotalt }}</b-nav-item>
    </b-nav>
  </div>
</template>

<script>
export default {
  props: [
    'numCorrect',
    'numTotalt'
  ]
}
</script>
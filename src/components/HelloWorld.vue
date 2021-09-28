<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div>
      <ul>
        <li><strong>{{ mail }}</strong></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
    mail: Array,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
ul {
  list-style-type: none;
  padding: 0;
}
li {
  margin: 0 10px;
  padding-top: 10px;
}
</style>

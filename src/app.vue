<div id="app">
<h1>{{message}}</h1>
</div>
<script>
var vm = newVue({
  el: "#app",
  data: {
    message: "Hello Vue!",
  },
});
</script>

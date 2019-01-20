<!DOCTYPE html>
<title>はじめてのVue.js</title>
<script src="https://unpkg.com/vue@2.5.17"></script>

<div id="app"></div>

<script>
new vue ({
  template: '<p>{{ msg }}</p>'
  data: { msg: 'hello world!'}
}).$mount('#app')
</script>
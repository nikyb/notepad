<template> 
<div>  
<button type="button" class="btn btn-primary">начоло</button>
<button type="button" class="btn btn-secondary">победители</button>
<button type="button" class="btn btn-success">проигравшие</button>
<button type="button" class="btn btn-danger">награждения</button>
<button type="button" class="btn btn-warning">Warning</button>

<h1> <span class="badge bg-secondary">областной турнир между 2006-2005 годов по футболу</span></h1>

<table class="table">
  <thead>
    <tr>
      <th scope="col">номера</th>
      <th scope="col">название команды</th>
      <th scope="col">город</th>
      <th scope="col">забитые голы</th>
      </thead>
    </tr>


</div>
</template>

<script>




export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

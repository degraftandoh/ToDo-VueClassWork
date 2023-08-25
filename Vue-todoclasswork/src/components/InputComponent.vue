
<script setup>

</script>

<template>
    <main class="container">
        <div class="inputBox">
      <p>TodoApp</p>
      <div class="links">
        <p><RouterLink to="/">Home</RouterLink></p>
        <p><RouterLink to="/task">Todos</RouterLink></p>
      </div>
    </div>
    </main>
</template>

<style scoped>
.container{
    padding: 27px 370px 0px 370px;
}
.inputBox{
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 10px;
  border-radius: 8px;
  background: #d53232;
  padding: 20px 42px;
}
.links{
  display: flex;
  align-items: center;
  gap: 24px;
}
</style>
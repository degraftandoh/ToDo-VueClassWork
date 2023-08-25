<script setup>
import InputComponent from "../components/InputComponent.vue";

</script>

<template>
  <main>
    
    <InputComponent />
    <div class="textBox">
      <div class="txt">
        <h1>Manage your tasks effectively</h1>
        <p>Modern todo list application to 
          help you track your activities and stay productive.
        </p>
        <button><RouterLink to="/task">Get Started</RouterLink></button>
      </div>
      <img src="../assets/hero-illustration.png"/>
    </div>
  
  </main>
</template>

<style scope>

.textBox{
  display: flex;
  padding-top: 50px;
  gap: 50px;
  padding: 27px 370px 0px 370px;
}
.txt{
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 20px;
}
</style>
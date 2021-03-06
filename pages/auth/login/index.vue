<template>
  <div class="container">
      <div class="row  p-3 mt-5 justify-content-center">
          <form class="form card col-md-4 p-3" v-on:submit.prevent="">
              <div class="form-group">
                  <label for="">Username:</label>
                  <input type="text" name="" id="" class="form-control">
              </div>
              <div class="form-group">
                  <label for="">Password:</label>
                  <input type="text" name="" id="" class="form-control">
              </div>
              <button class="btn btn-lg btn-primary mb-2" v-on:click="sayHi()">Acceder</button>
              <button class="btn btn-lg btn-outline-primary" v-on:click="sayHi()">Registrarse</button>
          </form>
      </div>
  </div>
</template>

<script lang="ts">
export default {
    methods:{
        sayHi: ()=>{
            console.log('Hola')
        }
    }
}
</script>

<style>

</style>
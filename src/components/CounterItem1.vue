<template>
    
  <div class="card" style="width: 18rem">
    <div class="card-body">
      <div class="card-title">
        <h1 class="card-title">{{ counter }}</h1>
      </div>

      <button
        style="margin-right: 2rem"
        @click="counter++"
        type="button"
        class="btn btn-outline-success"
      >
        Add
      </button>

      <button type="button" @click="counter--" class="btn btn-outline-danger">
        Reduce
      </button>
    </div>
  </div>
</template>

<script>
export default {

  data() {
    return {
      counter: 0,
    };
  },

};
</script>

<style>
.card-title {
  height: 250px;
  width: 250px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: rebeccapurple;
  color: aliceblue;
}
</style>

<template>
  <div class="hello">
<!-- <counter-Item1 @raiseCounter="ariseCounter" @redCounter="reduceCounter" :counter="counter"/> -->

<counter-Item1/>
<counter-Item1/>
<counter-Item1/>





  </div>
</template>

<script>
  import CounterItem1 from './CounterItem1'; 


export default {
  name: 'HelloWorld',
  components: {
  CounterItem1,

  

  },
  data() {
return{
  // counter:0
}
  },
  // methods:{
  //   ariseCounter(myCounter){
  // myCounter+=1
  //     this.counter = myCounter
     
    
  //   },
  //   reduceCounter(myCounter){
  // myCounter-=1
  //     this.counter = myCounter
     
    
  //   },
  // }
}
</script>


<style scoped>
  .hello {  
    display: flex;
   gap: 5rem;
  }

</style>

<template>
<button @click="handleClick" :class="['button', 'baseButton']">{{buttonText}}</button>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    buttonText:{
      type:String,
      default:()=>"Label",
    },
    light:{
      type:Boolean,
      default:()=> true,
    },
  },
  methods:{
    handleClick(){
      alert("Click me!");
    }
  }
 
}
</script>
<style scoped>
.button{
  background-color: rgb(87, 3, 3);
  color: white;
  border: 1px solid gray;
  cursor: pointer;
}
.baseButton{
  padding: 10px;
  border: none;
  border-radius: 10px;
  width: 100px;
}
</style>


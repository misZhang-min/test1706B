<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>
<script>
export default {
  data(){
    return {
       arr:[1,2,3,4,'a']
    }
  },
  created() {
    this.fun()
  },
  methods: {
    fun(){
      this.arr.forEach((item)=>{
        return console.log(item)
      })
    }
  },
}
</script>

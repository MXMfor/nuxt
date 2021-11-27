<template>
  <div>
    <Lol
      v-for="num in numbers"
      :key="num"
      :num="num"
    />
    <nuxt-link to="/user"><button>User</button></nuxt-link>
  </div>
</template>

<script>
export default {
  data(){
    return{
      numbers: [1,2,3,4,5,6,7]
    }
  },
  created(){
    console.log(this.numbers)
  }
}
</script>

<template>

  <div>

      <h2>The count is: {{ count }}</h2>


      <p>


          <button @click="count += 1">Increment by one</button>


      </p>

  </div>



</template>

<script>
export default {

    data() {
        return {count : 0}
    }
    
}
</script>

<style>



</style>
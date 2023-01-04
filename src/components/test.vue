<template>
    <h1 class="text-h2 font-weight-bold">Test 04</h1>
    <div>
      <v-slider
        :step="1"
        :max="10"
        color="orange"
        thumb-label
        prepend-icon="mdi-lightbulb-on-outline"
        >
        </v-slider>
  </div>
  </template>
<script>
 export default {
    data:function(){
        return 
        channel_id = undefined,
        channel_duty = undefined
    },
    mounted(){
        //console.log(channel_duty);
    }
 }
</script>
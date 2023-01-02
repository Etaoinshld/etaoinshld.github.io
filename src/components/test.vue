<template>
    <h1 class="text-h2 font-weight-bold">Test 03</h1>
    <div>
      <v-slider
        :step="1"
        :max="10"
        color="orange"
        thumb-label
        prepend-icon="mdi-lightbulb-on-outline"
        >
        <template v-slot:append>
          <v-text-field
            type="number"
            style="width: 80px"
            density="compact"
            hide-details
            variant="outlined"
          ></v-text-field>
        </template>
      ></v-slider>
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
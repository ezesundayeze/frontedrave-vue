<template>
  <div>
      <HeaderMenu/>
  </div>
</template>

<script>
import HeaderMenu from "@/views/Menu/index.vue";
export default {
    name:"Menu",
    components:{
        HeaderMenu
    },
    props:{
      msg:String
    }

}
</script>


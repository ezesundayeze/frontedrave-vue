<template>
  <div>
      <HeaderMenu/>
      <Sidebar/>
  </div>
</template>

<script>
import Sidebar from "@/App/features/Sidebar";
import HeaderMenu from "@/App/features/Menu/HeaderMenu"

export default {
    name:"dashboard",
    components:{
      Sidebar,
      HeaderMenu
    }
}
</script>

<template>
  <div>
      <Menu/>
      <Sidebar/>
  </div>
</template>

<script>
// @ is an alias to /src
import Dashboard from "@/App/features/Dashboard";
import Sidebar from "@/views/Sidebar";
import Menu from "@/views/Menu";
export default {
  name: "dashboard",
  components: {
  Dashboard, 
  Sidebar,
  Menu
  }
};
</script>

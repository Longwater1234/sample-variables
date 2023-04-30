<template>
  <el-menu
    :active-text-color="variables.menuActiveText"
    :background-color="variables.menuBg"
    :text-color="variables.menuText"
    :unique-opened="true"
    :collapse-transition="false"
    class="sidebar-menus"
  >
    <el-menu-item index="1">Menu 1</el-menu-item>
    <el-menu-item index="2">Menu 2</el-menu-item>
    <el-menu-item index="3">Menu 3</el-menu-item>
    <el-menu-item index="4">Menu 4</el-menu-item>
    <el-menu-item index="5">Menu 5</el-menu-item>
  </el-menu>
</template>
<script setup lang="ts">
import variables from "@/styles/variables.module.scss";
</script>

<template>
  <header id="header">
    <h1>汪汪旺影院</h1>
    <h2></h2>
  </header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
#header {
  width: 100%;
  height: 50px;
  color: #fff;
  background: #eb9f9f;
  border-bottom: 1px solid #eb9f9f;
  position: relative;
}
#header h1 {
  font-size: 18px;
  text-align: center;
  line-height: 50px;
  font-weight: normal;
}
#header i {
  position: absolute;
  left: 5px;
  top: 50%;
  margin-top: -13px;
  font-size: 26px;
}
</style>
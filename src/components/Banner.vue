<template>
  <div id="main-banner" style="background-image: url('/img/burger.jpg')">
    <h1>Make Your Burger</h1>
  </div>
</template>

<script>
export default {};
</script>
<style scoped>
#main-banner {
  background-position: 0 -250px;
  background-size: cover;
  height: 500px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}

#main-banner h1 {
  color: #fff;
  text-align: center;
  font-size: 60px;
  background-color: #222;
  padding: 20px 40px;
}
</style>

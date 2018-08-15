<template>
  <div class="container">
    <img src="~/assets/icon.svg">
    <div class="icon">
      icon-1
    </div>
  </div>
</template>
<style>
.container {
  padding: 100px;
}
.icon {
  width: 100px;
  height: 100px;
  background-image: url('~/assets/icon.svg'); /* this is NOT compiled. however, "2.0.0-25468832.6578bd7" version has no problem with compile */
  background-color: blue;
  color: #ffffff;
}
</style>

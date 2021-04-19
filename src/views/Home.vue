<template>
  <div class="home grid grid-cols-3 h-screen w-full">
    <div class="bg-color space-y-8">
      <div class="flex justify-center">
        <img src="../assets/logo.png " class="col-start-2 pt-20" />
      </div>

      <div class="space-y-6">
        <p class="font text-2xl Asul-font">Shabu & Yakiniku</p>
        <p class="font text-6xl Asul-font">Eat Else</p>
      </div>

      <div>
        <a
          href="/"
          class="click uppercase rounded-md  text-white px-4 py-3 transition 
          duration-300 ease-in-out hover:bg-white hover:bg-opacity-60 hover:text-white mr-6 Asul-font"
        >
          Go to site
        </a>
      </div>
    </div>

    <div class="col-span-2">
      <img src="../assets/background.png " />
    </div>
  </div>
</template>

<style scope>
.bg-color {
  background-color: #434343;
}
.font {
  color: #c4c4c4;
}
.click{
  background-color:#dfad2f;
}
.Asul-font{
  font-family: "Asul-font";
}
@font-face {
    font-family: "Asul-font";
    src: url("../font/Asul-Regular.ttf");
}
</style>
<script>
export default {};
</script>

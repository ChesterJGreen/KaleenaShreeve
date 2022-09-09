<template>
  <div class="flex-grow-1 container-fluid ">
    <div class="row">
      <div class="col-3 ">
        <img alt="logo" class="rounded-circle w-100 my-5"
          src="https://i.pinimg.com/280x280_RS/97/0e/3d/970e3dcfaa84c409f7879cce2d1c653e.jpg" />
      </div>
      <div class="col-9 px-5">
        <img class="w-100 mt-5 rounded elevation-3" src="src\assets\img\Stories.png">
      </div>
    </div>
    <div class="bg-white mt-5 row align-items-center home">
      <div class="col-12 p-5">
        <div class=" bg-warning lighten-10 row p-5 rounded-pill elevation-3">
          <div class="col-4 px-5">
            <img class="w-75 mx-3 rounded-circle border border-dark"
              src="https://th.bing.com/th/id/OIP.3wtQitk5ts9AzEepDVPyLAHaIy?pid=ImgDet&rs=1">
          </div>
          <div class="col-4 px-5">
            <img class="w-75 mx-3 rounded-circle border border-dark"
              src="https://www.bing.com/th?id=OIP.qtxvbuVcVvPSy-vYZlLwoQHaHa&w=250&h=250&c=8&rs=1&qlt=90&o=6&dpr=1.25&pid=3.1&rm=2">
          </div>
          <div class="col-4 px-5">
            <img class="w-75 mx-3 rounded-circle border border-dark"
              src="https://th.bing.com/th/id/R.506ce96b5875a2b4ce2515a19c94f30d?rik=HmHK4w1fN4l%2feQ&riu=http%3a%2f%2fclipartix.com%2fwp-content%2fuploads%2f2016%2f04%2fAmerican-flag-united-states-flag-clipart-3-clipartcow-2.png&ehk=2uh%2fEffAtPqEiKAozxozIzyS4a0XuWVi1W60RsggWCg%3d&risl=&pid=ImgRaw&r=0">
          </div>
          <div class="col-4 px-5">
            <h1 class="bg-success text-white p-3 rounded text-center">
              Life
            </h1>
          </div>
          <div class="col-4 px-5">
            <h1 class="bg-success text-white p-3 rounded text-center">
              Imagination
            </h1>
          </div>
          <div class="col-4 px-5">
            <h1 class="bg-success text-white p-3 rounded text-center">
              Faith
            </h1>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style scoped lang="scss">
.home {
  display: grid;
  height: 80vh;
  place-content: center;
  text-align: center;
  user-select: none;

  .home-card {
    width: 50vw;

    >img {
      height: 200px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }
}
</style>

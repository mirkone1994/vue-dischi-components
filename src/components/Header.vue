<template>
  <section>
      <div class="container">
          <div class="row align-items-center justify-content-between">
              <div class="col-1">
                  <img class="img-fluid" src="../images/logo.png" alt="">
              </div>
              <div class="col-1">
                  <select name="" id="">
                      <option value="">All</option>
                  </select>
              </div>
          </div>

      </div>

  </section>
</template>

<script>
export default {
    name: "Header",

}
</script>

<style scoped lang="scss">
    section {
        height: 50px;
        background-color: #2e3a46;
    }
    img {
        height: 50px;
    }

</style>
<template>
  <div id="app">
    <!-- header -->
    <global-nav></global-nav>

    <!-- main content -->
    <div class="container mt-5">
      <div class="row">
        <div class="col mx-auto">
          <!-- put dynamic components here -->
          <reg-form-one></reg-form-one>

        </div>
      </div>
    </div>

    <!-- footer -->

  </div>
</template>

<script>
import GlobalNav from "./components/header/GlobalNav";
import RegFormOne from "./components/student/RegFormOne";

export default {
  name: "app",
  components: {
    GlobalNav,
    RegFormOne
  }
};
</script>


<style lang="sass" scoped>

</style>


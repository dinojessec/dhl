<template>
  <div id="app">
    <!-- header -->
    <global-nav></global-nav>

    <!-- main content -->
    <div class="container mt-5">
      <div class="row">
        <div class="col mx-auto">
          <!-- put dynamic components here -->
          <reg-form-five></reg-form-five>

        </div>
      </div>
    </div>

    <!-- footer -->

  </div>
</template>

<script>
import GlobalNav from "./components/header/GlobalNav";
import RegFormFive from "./components/student/RegFormFive";

export default {
  name: "app",
  components: {
    GlobalNav,
    RegFormFive
  }
};
</script>


<style lang="sass" scoped>

</style>


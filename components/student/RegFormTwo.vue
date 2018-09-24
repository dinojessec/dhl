<template>

    <form>
        <h1>Address</h1>
        <div class="form-row">
            <div class="form-group col-md-6">
                <label for="inputHouseNumber">House Number</label>
                <input type="text" class="form-control" id="inputHouseNumber" placeholder="House Number, Floor Number, Building or Apartment Number">
            </div>
            <div class="form-group col-md-6">
                <label for="inputStreetName">Street Name</label>
                <input type="password" class="form-control" id="inputStreetName" placeholder="Street Name">
            </div>
        </div>
        <div class="form-row">
            <div class="form-group col-md-6">
                <label for="inputBarangay">Barangay</label>
                <input type="text" class="form-control" id="inputBarangay" placeholder="Barangay">
            </div>
            <div class="form-group col-md-6">
                <label for="inputTown">Town</label>
                <input type="text" class="form-control" id="inputTown" placeholder="Town">
            </div>
        </div>
        <div class="form-row">
            <div class="form-group col-md-6">
                <label for="inputCity">City</label>
                <input type="text" class="form-control" id="inputCity" placeholder="City">
            </div>
        </div>
        <!-- fatheraddress -->
        <h1>Father Address</h1>
        <div class="form-check">
            <input class="form-check-input" type="checkbox" value="" id="fatherCheck">
            <label class="form-check-label" for="fatherCheck">
                Address same as above.
            </label>
        </div>
        <div class="form-row">
            <div class="form-group col-md-6">
                <label for="inputHouseNumber">House Number</label>
                <input type="text" class="form-control" id="inputHouseNumber" placeholder="House Number, Floor Number, Building or Apartment Number">
            </div>
            <div class="form-group col-md-6">
                <label for="inputStreetName">Street Name</label>
                <input type="password" class="form-control" id="inputStreetName" placeholder="Street Name">
            </div>
        </div>
        <div class="form-row">
            <div class="form-group col-md-6">
                <label for="inputBarangay">Barangay</label>
                <input type="text" class="form-control" id="inputBarangay" placeholder="Barangay">
            </div>
            <div class="form-group col-md-6">
                <label for="inputTown">Town</label>
                <input type="text" class="form-control" id="inputTown" placeholder="Town">
            </div>
        </div>
        <div class="form-row">
            <div class="form-group col-md-6">
                <label for="inputCity">City</label>
                <input type="text" class="form-control" id="inputCity" placeholder="City">
            </div>
        </div>
        <!-- motheraddress -->
        <h1>Mother Address</h1>
        <div class="form-check">
            <input class="form-check-input" type="checkbox" value="" id="motherCheck">
            <label class="form-check-label" for="motherCheck">
                Address same as above.
            </label>
        </div>
        <div class="form-row">
            <div class="form-group col-md-6">
                <label for="inputHouseNumber">House Number</label>
                <input type="text" class="form-control" id="inputHouseNumber" placeholder="House Number, Floor Number, Building or Apartment Number">
            </div>
            <div class="form-group col-md-6">
                <label for="inputStreetName">Street Name</label>
                <input type="password" class="form-control" id="inputStreetName" placeholder="Street Name">
            </div>
        </div>
        <div class="form-row">
            <div class="form-group col-md-6">
                <label for="inputBarangay">Barangay</label>
                <input type="text" class="form-control" id="inputBarangay" placeholder="Barangay">
            </div>
            <div class="form-group col-md-6">
                <label for="inputTown">Town</label>
                <input type="text" class="form-control" id="inputTown" placeholder="Town">
            </div>
        </div>
        <div class="form-row">
            <div class="form-group col-md-6">
                <label for="inputCity">City</label>
                <input type="text" class="form-control" id="inputCity" placeholder="City">
            </div>
        </div>
        <button type="submit" class="btn btn-primary">Next</button>
    </form>

</template>

<script>
export default {
  name: "RegFormTwo"
};
</script>


<style lang="scss" scoped>
</style>

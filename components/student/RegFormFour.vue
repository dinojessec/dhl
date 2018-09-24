<template>

    <form>
        <h1>Education</h1>
        <div class="form-row">
            <div class="form-group col-md-4">
                <label for="inputElem">Elementary</label>
                <input type="text" class="form-control" id="inputElem" placeholder="Elementary">
            </div>
            <div class="form-group col-md-4">
                <label for="inputElemYear">Year Graduated</label>
                <input type="text" class="form-control" id="inputElemYear" placeholder="Elementary Year Graduated">
            </div>
            <div class="form-group col-md-4">
                <label for="inputElemHonors">Elementary Accolades</label>
                <input type="text" class="form-control" id="fatherName" placeholder="Honors/Awards/Recognition">
            </div>
        </div>
        <div class="form-row">
            <div class="form-group col-md-4">
                <label for="inputJHS">Junior High School</label>
                <input type="text" class="form-control" id="inputJHS" placeholder="Junior High School">
            </div>
            <div class="form-group col-md-4">
                <label for="inputJHSYear">Year Graduated</label>
                <input type="text" class="form-control" id="inputJHSYear" placeholder="Junior High School Year Graduated">
            </div>
            <div class="form-group col-md-4">
                <label for="inputJHSHonors">Junior High School Accolades</label>
                <input type="text" class="form-control" id="inputJHSHonors" placeholder="Honors/Awards/Recognition">
            </div>
        </div>
        <div class="form-row">
            <div class="form-group col-md-4">
                <label for="inputTypeofSchool">School type</label>
                <select id="inputTypeofSchool" class="form-control">
                    <option selected>Select</option>
                    <option>Private</option>
                    <option>Public</option>
                </select>
            </div>
            <div class="form-group col-md-4">
                <label for="inputLocationofFormerSchool">Location of Previous School</label>
                <input type="text" class="form-control" id="inputLocationofFormerSchool" placeholder="Town where the school is located">
            </div>
            <div class="form-group col-md-4">
                <label for="inputVoucher">Voucher</label>
                <input type="text" class="form-control" id="inputVoucher" placeholder="Voucher">
            </div>
        </div>
        <div class="form-row">
            <div class="form-group col-md-4">
                <label for="inputOrg">Organization</label>
                <input type="text" class="form-control" id="inputOrg" placeholder="Organizations/Clubs">
            </div>
            <div class="form-group col-md-4">
                <label for="inputOrgAward">Awards in the said Organization</label>
                <input type="text" class="form-control" id="inputOrgAward" placeholder="Awards/Honors">
            </div>
            <div class="form-group col-md-4">
                <label for="inputPreferredCourse">Preferred Course in College</label>
                <input type="text" class="form-control" id="inputPreferredCourse" placeholder="Preferred Course">
            </div>
        </div>
        <button type="submit" class="btn btn-primary">Next</button>
    </form>

</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
</style>

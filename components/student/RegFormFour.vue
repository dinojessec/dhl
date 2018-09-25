<template>

    <form>
        <div class="form-group">
            <b-form-group label="Personal Information" label-size="lg" label-class="font-weight-bold pt-0" class="mb-2">
                <b-card bg-variant="light">
                    <!-- 1st row -->
                    <b-col>
                        <b-input-group>
                            <b-form-group row label="Elementary:" label-class="text-sm-right" label-for="elementary" class="col-4">
                                <b-form-input id="elementary"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="Year Graduated:" label-class="text-sm-right" label-for="elemYearGraduated" class="col-4">
                                <b-form-input id="elemYearGraduated"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="Elementary Honors and Awards:" label-class="text-sm-right" label-for="elemHonors" class="col-4">
                                <b-form-input id="elemHonors"></b-form-input>
                            </b-form-group>
                        </b-input-group>
                    </b-col>
                    <!-- 2ndrow -->
                    <b-col>
                        <b-input-group>
                            <b-form-group row label="Junior High School:" label-class="text-sm-right" label-for="jhs" class="col-4">
                                <b-form-input id="jhs"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="Year Graduated:" label-class="text-sm-right" label-for="jhsYearGraduated" class="col-4">
                                <b-form-input id="jhsYearGraduated"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="Junior High School Honors and Awards:" label-class="text-sm-right" label-for="jhsHonors" class="col-4">
                                <b-form-input id="jhsHonors"></b-form-input>
                            </b-form-group>
                        </b-input-group>
                    </b-col>
                    <!-- 3rdrow -->
                    <b-col>
                        <b-input-group>
                            <b-form-group row label="School Type:" class="col-4">
                                <b-form-radio-group class="pt-2" :options="['Private', 'Public']" />
                            </b-form-group>
                            <b-form-group row label="Former School Location:" label-class="text-sm-right" label-for="formerSchoolLocatioin" class="col-4">
                                <b-form-input id="formerSchoolLocatioin"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="Voucher:" label-class="text-sm-right" label-for="voucher" class="col-4">
                                <b-form-input id="voucher"></b-form-input>
                            </b-form-group>
                        </b-input-group>
                    </b-col>
                    <!-- 4throw -->
                    <b-col>
                        <b-input-group>
                            <b-form-group row label="Organization" label-class="text-sm-right" label-for="organization" class="col-4">
                                <b-form-input id="organization"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="Organization Awards" label-class="text-sm-right" label-for="organizationAward" class="col-4">
                                <b-form-input id="organizationAward"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="Preferred Course in College:" label-class="text-sm-right" label-for="preferredCourse" class="col-4">
                                <b-form-input id="preferredCourse"></b-form-input>
                            </b-form-group>
                        </b-input-group>
                    </b-col>
                    <!-- 5throw -->
                    <b-col>
                        <b-input-group>
                            <b-form-group row label="Preferred Shift:" class="col-12">
                                <b-form-radio-group class="pt-2" :options="['AM', 'PM']" />
                            </b-form-group>
                        </b-input-group>
                    </b-col>
                    <button type="submit" class="btn btn-primary float-right">Next</button>
                </b-card>
            </b-form-group>
        </div>
    </form>

</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
</style>

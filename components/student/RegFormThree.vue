<template>

    <form>

        <div class="form-group">
            <b-form-group label="Parents Information" label-size="lg" label-class="font-weight-bold pt-0" class="mb-2">
                <b-card bg-variant="light">
                    <!-- 1st line -->
                    <b-col>
                        <b-form-group label="Father Information" label-size="lg" label-class="font-weight-bold pt-0" class="mb-2">
                            <b-input-group>
                                <b-form-group row label="Father Name:" label-class="text-sm-right" label-for="fatherName" class="col-6">
                                    <b-form-input id="fatherName"></b-form-input>
                                </b-form-group>
                            </b-input-group>
                        </b-form-group>
                    </b-col>
                    <b-col>
                        <b-input-group>
                            <b-form-group row label="Occupation:" label-class="text-sm-right" label-for="fatherOccupation" class="col-4">
                                <b-form-input id="fatherOccupation"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="Employer:" label-class="text-sm-right" label-for="fatherEmployer" class="col-4">
                                <b-form-input id="fatherEmployer"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="Employer Address:" label-class="text-sm-right" label-for="fatherEmployerAddress" class="col-4">
                                <b-form-input id="fatherEmployerAddress"></b-form-input>
                            </b-form-group>
                        </b-input-group>
                    </b-col>
                    <b-col>
                        <b-input-group>
                            <b-form-group row label="Highest Educational Attainment:" label-class="text-sm-right" label-for="fatherEducAttainment" class="col-4">
                                <b-form-input id="fatherEducAttainment"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="School Graduated:" label-class="text-sm-right" label-for="fatherSchoolGraduated" class="col-4">
                                <b-form-input id="fatherSchoolGraduated"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="Religion:" label-class="text-sm-right" label-for="fatherReligion" class="col-4">
                                <b-form-input id="fatherReligion"></b-form-input>
                            </b-form-group>
                        </b-input-group>
                    </b-col>
                    <b-col>
                        <b-input-group>
                            <b-form-group row label="Mobile Number:" label-class="text-sm-right" label-for="fatherMobileNumber" class="col-6">
                                <b-form-input id="fatherMobileNumber"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="Landline Number:" label-class="text-sm-right" label-for="fatherLandlineNumber" class="col-6">
                                <b-form-input id="fatherLandlineNumber"></b-form-input>
                            </b-form-group>
                        </b-input-group>
                    </b-col>
                    <!-- mother -->
                    <b-col>
                        <b-form-group label="Mother Information" label-size="lg" label-class="font-weight-bold pt-0" class="mb-2">
                            <b-input-group>
                                <b-form-group row label="Mother Name:" label-class="text-sm-right" label-for="motherName" class="col-6">
                                    <b-form-input id="motherName"></b-form-input>
                                </b-form-group>
                            </b-input-group>
                        </b-form-group>
                    </b-col>
                    <b-col>
                        <b-input-group>
                            <b-form-group row label="Occupation:" label-class="text-sm-right" label-for="motherOccupation" class="col-4">
                                <b-form-input id="motherOccupation"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="Employer:" label-class="text-sm-right" label-for="motherEmployer" class="col-4">
                                <b-form-input id="motherEmployer"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="Employer Address:" label-class="text-sm-right" label-for="motherEmployerAddress" class="col-4">
                                <b-form-input id="motherEmployerAddress"></b-form-input>
                            </b-form-group>
                        </b-input-group>
                    </b-col>
                    <b-col>
                        <b-input-group>
                            <b-form-group row label="Highest Educational Attainment:" label-class="text-sm-right" label-for="motherEducAttainment" class="col-4">
                                <b-form-input id="motherEducAttainment"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="School Graduated:" label-class="text-sm-right" label-for="motherSchoolGraduated" class="col-4">
                                <b-form-input id="motherSchoolGraduated"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="Religion:" label-class="text-sm-right" label-for="motherReligion" class="col-4">
                                <b-form-input id="motherReligion"></b-form-input>
                            </b-form-group>
                        </b-input-group>
                    </b-col>
                    <b-col>
                        <b-input-group>
                            <b-form-group row label="Mobile Number:" label-class="text-sm-right" label-for="motherMobileNumber" class="col-6">
                                <b-form-input id="motherMobileNumber"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="Landline Number:" label-class="text-sm-right" label-for="motherLandlineNumber" class="col-6">
                                <b-form-input id="motherLandlineNumber"></b-form-input>
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
</script>

<style lang="scss" scoped>
</style>

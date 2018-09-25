<template>

    <form>

        <div class="form-group">
            <b-form-group label="Address" label-size="lg" label-class="font-weight-bold pt-0" class="mb-2">
                <b-card bg-variant="light">

                    <!-- student address -->
                    <b-col>
                        <b-form-group label="Present Address" label-size="lg" label-class="font-weight-bold pt-0" class="mb-0">
                            <b-input-group>
                                <b-form-group row label="House Number:" label-class="text-sm-right" label-for="houseNumber" class="col-3">
                                    <b-form-input id="houseNumber"></b-form-input>
                                </b-form-group>
                                <b-form-group row label="Street Name:" label-class="text-sm-right" label-for="streetName" class="col-5">
                                    <b-form-input id="streetName"></b-form-input>
                                </b-form-group>
                                <b-form-group row label="Barangay:" label-class="text-sm-right" label-for="barangay" class="col-4">
                                    <b-form-input id="barangay"></b-form-input>
                                </b-form-group>
                            </b-input-group>
                        </b-form-group>
                    </b-col>
                    <b-col>
                        <b-input-group>
                            <b-form-group row label="Town:" label-class="text-sm-right" label-for="town" class="col-6">
                                <b-form-input id="town"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="City:" label-class="text-sm-right" label-for="city" class="col-6">
                                <b-form-input id="city"></b-form-input>
                            </b-form-group>
                        </b-input-group>
                    </b-col>
                    <!-- fatheraddress -->
                    <b-col>
                        <b-form-group label="Father Address" label-size="lg" label-class="font-weight-bold pt-0" class="mb-0">
                            <b-form-checkbox id="checkbox1" value="accepted" unchecked-value="not_accepted" class="mb-2">
                                Address same as above.
                            </b-form-checkbox>
                            <b-input-group>
                                <b-form-group row label="House Number:" label-class="text-sm-right" label-for="fatherHouseNumber" class="col-3">
                                    <b-form-input id="fatherHouseNumber"></b-form-input>
                                </b-form-group>
                                <b-form-group row label="Street Name:" label-class="text-sm-right" label-for="fatherStreetName" class="col-5">
                                    <b-form-input id="fatherStreetName"></b-form-input>
                                </b-form-group>
                                <b-form-group row label="Barangay:" label-class="text-sm-right" label-for="fatherBarangay" class="col-4">
                                    <b-form-input id="fatherBarangay"></b-form-input>
                                </b-form-group>
                            </b-input-group>
                        </b-form-group>
                    </b-col>
                    <b-col>
                        <b-input-group>
                            <b-form-group row label="Town:" label-class="text-sm-right" label-for="fatherTown" class="col-6">
                                <b-form-input id="fatherTown"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="City:" label-class="text-sm-right" label-for="fatherCity" class="col-6">
                                <b-form-input id="fatherCity"></b-form-input>
                            </b-form-group>
                        </b-input-group>
                    </b-col>
                    <!-- motheraddress -->
                    <b-col>
                        <b-form-group label="Mother Address" label-size="lg" label-class="font-weight-bold pt-0" class="mb-0">
                            <b-form-checkbox id="checkbox2" value="accepted" unchecked-value="not_accepted" class="mb-2">
                                Address same as above.
                            </b-form-checkbox>
                            <b-input-group>
                                <b-form-group row label="House Number:" label-class="text-sm-right" label-for="motherHouseNumber" class="col-3">
                                    <b-form-input id="motherHouseNumber"></b-form-input>
                                </b-form-group>
                                <b-form-group row label="Street Name:" label-class="text-sm-right" label-for="motherStreetName" class="col-5">
                                    <b-form-input id="motherStreetName"></b-form-input>
                                </b-form-group>
                                <b-form-group row label="Barangay:" label-class="text-sm-right" label-for="motherBarangay" class="col-4">
                                    <b-form-input id="motherBarangay"></b-form-input>
                                </b-form-group>
                            </b-input-group>
                        </b-form-group>
                    </b-col>
                    <b-col>
                        <b-input-group>
                            <b-form-group row label="Town:" label-class="text-sm-right" label-for="motherTown" class="col-6">
                                <b-form-input id="motherTown"></b-form-input>
                            </b-form-group>
                            <b-form-group row label="City:" label-class="text-sm-right" label-for="motherCity" class="col-6">
                                <b-form-input id="motherCity"></b-form-input>
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
export default {
  name: "RegFormTwo"
};
</script>


<style lang="scss" scoped>
</style>

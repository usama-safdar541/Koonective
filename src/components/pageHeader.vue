<template>
    <div class="header">
        <b-container>
            <b-row>
                <b-col>
                    <div class="header-content">
                        <div class="help-contact">
                            <span>Help&Contact</span>
                            <hr>
                            <span>Contact us free: +1-541-754-3010</span>
                        </div>
                        <div class="help-contact">
                            <div><i class="fa fa-thin fa-user"></i><span>Sign In/Register</span></div>
                            <hr>
                            <span>ENG</span>
                        </div>
                    </div>
                </b-col>

            </b-row>
        </b-container>
    </div>
</template>
<script>
export default {

}
</script>
<style scoped>
.header-content {
    /* width:30%; */
    display: flex;
    justify-content: space-between;
    gap: 1rem;
    max-width: 1300px;
    margin: auto;
    padding: 10px;
}

.help-contact {
    display: flex;
    justify-content: space-between;
    gap: 1rem;
}

hr {
    height: 25px;
    margin: 0px;
}


</style>
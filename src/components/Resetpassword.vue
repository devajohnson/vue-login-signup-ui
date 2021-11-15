<template>
    <div class="vue-tempalte">

        <form>

            <h3>Reset Password</h3>

            <div class="form-group">
                <label>Enter OPT Send to phone or Email</label>
                <!-- <input type="number || text" class="form-control form-control-lg" /> -->
                <input v-model="OPT"
                    oninput="javascript: if (this.value.length > this.maxLength) this.value = this.value.slice(0, this.maxLength);"
                    type = "number || text"
                     maxlength = "6"/>
            </div>

            <button type="submit" class="btn btn-dark btn-lg btn-block">Submit</button>

        </form>

    </div>
</template>

<script>

    export default {
        data() {
            return {}
        }
    }
    
</script>
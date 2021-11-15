<template>
    <div class="vue-tempalte">
        <form>
            <h3>Forgot Password</h3>

            <div class="form-group">
                <label>Email address(or)Phone number</label>
                <input type="email || number" class="form-control form-control-lg" />
            </div>

            <!-- <button type="submit" class="btn btn-dark btn-lg btn-block">Reset password</button> -->
            <router-link to="/reset-password" tag="button">Reset Password</router-link>
        

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
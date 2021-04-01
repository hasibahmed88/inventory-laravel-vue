<template>
    <div class="register">
        <div class="container">
             <div class="d-flex align-items-center justify-content-center ht-md-100v">

            <div class="login-wrapper wd-300 wd-xs-400 pd-25 pd-xs-40 bg-white">
                <div class="signin-logo tx-center tx-24 tx-bold tx-inverse">Register</div>
                <br>
                <div class="form-group">
                <input type="text" class="form-control" name="name" placeholder="Full name">
                </div>
                <div class="form-group">
                <input type="email" class="form-control" name="email" placeholder="Email address">
                </div>
                <div class="form-group">
                <input type="password" class="form-control" name="pasword" placeholder="Password">
                </div>
                <div class="form-group">
                <input type="password" class="form-control" name="confirm_password" placeholder="Confirm Password">
                </div>
                <br>
                <button type="submit" class="btn btn-info btn-block">Register</button>

                <div class="mg-t-40 tx-center">Already have an account? <router-link to="/" class="tx-info">Login here</router-link></div>
            </div><!-- login-wrapper -->
            </div><!-- d-flex -->
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

</style>
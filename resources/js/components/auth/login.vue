<template>
    <div class="login">
        <div class="container">
            <div class="d-flex align-items-center justify-content-center ht-100v">

            <div class="login-wrapper wd-300 wd-xs-350 pd-25 pd-xs-40 bg-white">
                <div class="signin-logo tx-center tx-24 tx-bold tx-inverse">Login</div>
                <br>
                <div class="form-group">
                <input type="email" class="form-control" name="email" placeholder="Email address">
                </div><!-- form-group -->
                <div class="form-group">
                <input type="password" class="form-control" name="password" placeholder="Enter your password">
                <router-link to="/forget-password" class="tx-info tx-12 d-block mg-t-10">Forgot password?</router-link>
                </div><!-- form-group -->
                <button type="submit" class="btn btn-info btn-block">Login</button>

                <div class="mg-t-40 tx-center">Not yet a member? <router-link to="/register" class="tx-info">Register here</router-link></div>
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
<script setup>
</script>
<template>
    <Head>
        <title>Sign Up</title>
    </Head>
    <div>
        <div class="container-xxl d-flex align-items-center justify-content-center flex-column p-xs-2" style="width: 100%; height: 100vh;">
            <div class="border rounded p-5 d-flex flex-column col-12 col-sm-8 col-lg-4">
                <h1 class="fw-bold text-center">Sign Up</h1>
                <p class="text-center">Create a new account.</p>
                <form action="" class="px-2">
                    <div class="mb-3">
                        <label for="formGroupExampleInput" class="form-label">Username</label>
                        <input type="text" class="form-control" placeholder="Enter your username" aria-describedby="inputGroup-sizing-default">
                    </div>
                    <div class="mb-3">
                        <label for="formGroupExampleInput" class="form-label">Username</label>
                        <input type="email" class="form-control" placeholder="Enter your email" aria-describedby="inputGroup-sizing-default">
                    </div>
                    <div class="mb-3">
                        <label for="formGroupExampleInput" class="form-label">Password</label>
                        <input type="password" class="form-control" placeholder="Enter your password" aria-describedby="inputGroup-sizing-default">
                    </div>
                    <button type="submit" class="btn btn-primary rounded" style="width: 100%;">Register</button>
                    <p class="mt-2 text-center">Already have an account?
                        <Link class="link-underline link-underline-opacity-0 link-underline link-underline-opacity-100-hover ms-1" href="/">Log In</Link>
                    </p>
                </form>
            </div>
        </div>
    </div>
</template>
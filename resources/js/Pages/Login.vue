<script setup>
    import { Link, Head } from '@inertiajs/vue3';
</script>
<template>
    <Head>
        <title>Sign In</title>
    </Head>
    <div>
        <div class="container-xxl d-flex align-items-center justify-content-center flex-column p-xs-2" style="width: 100%; height: 100vh;">
            <div class="border rounded p-5 d-flex flex-column flex-column col-12 col-sm-8 col-lg-4">
                <h1 class="fw-bold text-center">Sign In</h1>
                <p class="text-center">Welcome back, you've been missed!</p>
                <form action="" class="px-2">
                    <div class="mb-3">
                        <label for="formGroupExampleInput" class="form-label">Username</label>
                        <input type="text" class="form-control" placeholder="OnezPH or Onez.ph.dev@gmail.com" aria-describedby="inputGroup-sizing-default">
                    </div>
                    <div class="mb-3">
                        <label for="formGroupExampleInput" class="form-label">Password</label>
                        <input type="password" class="form-control" placeholder="Enter your Password" aria-describedby="inputGroup-sizing-default">
                    </div>
                    <div class="mb-3 me-auto form-check">
                        <input type="checkbox" class="form-check-input" id="exampleCheck1">
                        <label class="form-check-label" for="exampleCheck1">Remember me</label>
                    </div>
                    <button type="submit" class="btn btn-primary rounded" style="width: 100%;">Login</button>
                    <p class="mt-2 text-center">You haven't any account?
                        <Link class="link-underline link-underline-opacity-0 link-underline link-underline-opacity-100-hover ms-1" href="/signup">Sign Up</Link>
                    </p>
                </form>
            </div>
        </div>
    </div>
</template>
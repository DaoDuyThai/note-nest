<template>
    <div class="bg-black h-screen">
        <!-- sidebar  -->
        <div class="w-[516px] p-8">
            <Logo />
            <h1 class="text-white text-[18px] font-bold">Sign up for a free account</h1>
            <p class="text-white text-sm">Already registed? <span
                    class="underline text-yellow-400 font-bold">Login</span> to your
                account</p>
            <div class="mt-12">
                <label for="email" class="text-white text-sm block mb-0.5">Email Address</label>
                <input type="email" placeholder="you@example.com"
                    class="text-white rounded-md p-2 block w-full bg-zinc-800">
            </div>

            <div class="mt-5">
                <label for="password" class="text-white text-sm block mb-0.5">Password</label>
                <input type="password" placeholder="*******************" class="text-white rounded-md p-2 block w-full bg-zinc-800">
            </div>
            <div>
                <button class="w-full text-black bg-yellow-400 p-2 font-bold rounded-full mt-5">
                    Sign Up
                </button>
            </div>
        </div>
        <!-- /sidebar -->
        <!-- Note introduction -->
        <div>

        </div>
        <!-- /Note introduction -->

    </div>
</template>

<template>
    <div class="flex flex-col justify-center items-center w-screen h-screen">
        <div class="w-[20%] h-[40%] bg-slate-100 shadow-slate-600 shadow-md">
            <div class="flex justify-center items-center pt-3">
                <h5 class="font-bold text-lg">Login</h5>
            </div>
            <div class="flex flex-col my-6 mx-5">
                <label for="email" class="mb-5">Email</label>
                <input type="text" name="email" id="" placeholder="Email"
                    class="h-10 px-2 border-cyan-800 border-2 rounded-md focus:text-cyan-700">
            </div>
            <div class="flex flex-col my-6 mx-5">
                <label for="email" class="mb-5">Password</label>
                <input type="password" name="password" id="" placeholder="password"
                    class="h-10 px-2 border-cyan-800 border-2 rounded-md focus:text-cyan-700">
            </div>
            <div class="mt-12 flex items-center justify-center">
                <button
                    class="w-32 h-10 flex items-center justify-center bg-slate-600 text-white font-extrabold rounded-lg">SUBMIT</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    head: {
        title: "Login Page",
    },
    name: "LoginPage"
}
</script>
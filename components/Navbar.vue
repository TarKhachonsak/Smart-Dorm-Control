<template>
  <nav class="bg-white shadow-md">
    <div id="menu" class="flex justify-between items-center px-12">
        <div id="logo">
            <a href="#"><img src="public/logo.png" class="size-20"></a>
        </div>
        <ul class="flex font-bold text-black ">
            <li class="hover:text-[#0075BE] p-3"><a href="#">หน้าแรก</a></li>
            <li class="hover:text-[#0075BE] p-3"><a href="#">การชำระเงิน</a></li>
            <li class="hover:text-[#0075BE] p-3"><a href="#">ติดต่อเรา</a></li>
            <li class="hover:text-[#0075BE] p-3"><a href="#">เกี่ยวกับเรา</a></li>
        </ul>
        <div id="message-profile" class="flex justify-center">
            <div class="px-2 py-1 m-1 flex items-center justify-center hover:bg-slate-200">
                <a href="#" class=""><i class="fa-regular fa-envelope"></i></a>
            </div>
            <div class="px-2 py-1 m-1 flex items-center justify-center hover:bg-slate-200">
                <a href="#" class=""><i class="fa-regular fa-user"></i></a>
            </div>
        </div>
    </div>
  </nav>
</template>

<script>
export default {

}
</script>

<style scoped>

</style>
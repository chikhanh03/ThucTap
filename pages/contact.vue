<template>
    <div class="flex mb-20">
        <div class="bg-[url('/img/page-bg.jpg')] h-[350px] w-full bg-center">
            <div class="mt-36 text-center uppercase">
                <div class="text-cyan-50 text-4xl mb-7">
                    <p>Liên hệ</p>
                </div>
                <div class="text-cyan-50">
                    <NuxtLink to="/">TRANG CHỦ</NuxtLink>&ensp;/&ensp;liên hệ
                </div>
            </div>
        </div>
    </div>

    <div class="flex md:flex-row 2xl:px-36 px-10 flex-col">
        <div class="md:w-4/12 mr-10 mb-20">
            <div class="flex flex-col">
                <div class="text-4xl mb-5">ĐỊA CHỈ:</div>
                <div class="flex flex-row">
                    <div class="mb-5"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                            stroke-width="1.5" stroke="currentColor" class="w-5 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" />
                        </svg>
                    </div>
                    <div class="ml-3">56 Vân côi, Q. Tân Bình, Tp.HCM</div>
                </div>
                <div class="text-4xl mb-5">ĐIỆN THOẠI:</div>
                <div class="flex flex-row mb-3">
                    <div><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" class="w-5 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z" />
                        </svg>
                    </div>
                    <div class="ml-3">1900636099</div>
                </div>
                <div class="flex flex-row mb-5">
                    <div><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" class="w-5 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M15.75 15.75V18m-7.5-6.75h.008v.008H8.25v-.008zm0 2.25h.008v.008H8.25V13.5zm0 2.25h.008v.008H8.25v-.008zm0 2.25h.008v.008H8.25V18zm2.498-6.75h.007v.008h-.007v-.008zm0 2.25h.007v.008h-.007V13.5zm0 2.25h.007v.008h-.007v-.008zm0 2.25h.007v.008h-.007V18zm2.504-6.75h.008v.008h-.008v-.008zm0 2.25h.008v.008h-.008V13.5zm0 2.25h.008v.008h-.008v-.008zm0 2.25h.008v.008h-.008V18zm2.498-6.75h.008v.008h-.008v-.008zm0 2.25h.008v.008h-.008V13.5zM8.25 6h7.5v2.25h-7.5V6zM12 2.25c-1.892 0-3.758.11-5.593.322C5.307 2.7 4.5 3.65 4.5 4.757V19.5a2.25 2.25 0 002.25 2.25h10.5a2.25 2.25 0 002.25-2.25V4.757c0-1.108-.806-2.057-1.907-2.185A48.507 48.507 0 0012 2.25z" />
                        </svg>
                    </div>
                    <div class="ml-3">1900636099</div>
                </div>
                <div class="text-4xl mb-5">EMAIL:</div>
                <div class="flex flex-row">
                    <div><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" class="w-5 h-5">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75" />
                        </svg>
                    </div>
                    <div class="ml-3">hi@haravan.com</div>
                </div>
            </div>
        </div>
        <div class="md:w-8/12">
            <div class="text-4xl mb-5">LIÊN HỆ:</div>
            <div class="flex md:flex-row flex-col mb-5">
                <div class="flex flex-col">
                    <label class="mb-1" for="">Tên*</label>
                    <input class="bg-slate-200 border-2 border-gray-300 md:w-40 xl:w-60 lg:w-52 h-10 pl-3 md:mr-3" type="text" name="" id="">
                </div>
                <div class="flex flex-col">
                    <label class="mb-1" for="">Email*</label>
                    <input class="bg-slate-200 border-2 border-gray-300 md:w-40 xl:w-60 lg:w-52 h-10 pl-3 md:mr-3" type="email" name="" id="">
                </div>
                <div class="flex flex-col">
                    <label class="mb-1" for="">Số điện thoại*</label>
                    <input class="bg-slate-200 border-2 border-gray-300 md:w-40 xl:w-60 lg:w-52 h-10 pl-3" type="text" name="" id="">
                </div>
            </div>
            <div class="flex flex-col">
                <label class="mb-1" for="">Nội dung*</label>
                <input class="bg-slate-200 border-2 border-gray-300 md:w-[505px] xl:w-full lg:w-[650px] h-52 pl-3" type="text" name="" id="">
            </div>
            <div>
                <button class=" border-2 border-black hover:bg-slate-500 px-5 py-2 mt-10 hover:text-white mb-10">
                    GỬI LIÊN HỆ
                </button>
            </div>
        </div>
    </div>

    <div class="mb-20 mt-10">
        <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3919.310729061172!2d106.6539626784669!3d10.787496261978522!
            2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31752ecbb6275cc3%3A0x634b1cfb9f2ed0be!2zNTYgVsOibiBDw7RpLCBwaMaw4bud
            bmcgNywgVMOibiBCw6xuaCwgSOG7kyBDaMOtIE1pbmgsIFZpZXRuYW0!5e0!3m2!1sen!2s!4v1446015505979"
            frameborder="0" width="100%" height="350"></iframe>
    </div>
    <p class="mb-32 md:mx-36 mx-10">Copyright © 2023 Pixel Company. Powered by Haravan.</p>
</template>

<script setup>

</script>

<style scoped>

textarea {
    width: 745px;
}
</style>
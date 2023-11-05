<template>
    <div class="flex mb-20">
        <div class="bg-[url('/img/page-bg.jpg')] h-[350px] w-full bg-center">
            <div class="mt-36 text-center">
                <div class="text-cyan-50 text-4xl mb-7">
                    <p>GIỚI THIỆU</p>
                </div>
                <div class="text-cyan-50">
                    <NuxtLink to="/">TRANG CHỦ</NuxtLink>&ensp;/&ensp;GIỚI THIỆU
                </div>
            </div>
        </div>
    </div>

    <div class="flex lg:flex-row flex-col 2xl:mx-36 mx-10 mb-20">
        <div class="lg:w-1/2 mb-5">
            <img class="lg:w-[540px] lg:h-[540px] sm:w-[690px] sm:h-[690px] w-auto h-auto mx-auto"
                src="https://theme.hstatic.net/1000122243/1000533602/14/image-intro3.jpg?v=45" alt="" />
        </div>
        <div class="lg:w-1/2 lg:ml-5 mx-auto">
            <p class="mb-8">
                Trang giới thiệu giúp khách hàng hiểu rõ hơn về cửa hàng của bạn. Hãy
                cung cấp thông tin cụ thể về việc kinh doanh, về cửa hàng, thông tin
                liên hệ. Điều này sẽ giúp khách hàng cảm thấy tin tưởng khi mua hàng
                trên website của bạn.
            </p>
            <p class="mb-8">Một vài gợi ý cho nội dung trang Giới thiệu:</p>
            <ul class="mb-8">
                <li>Bạn là ai</li>
                <li>Giá trị kinh doanh của bạn là gì</li>
                <li>Địa chỉ cửa hàng</li>
                <li>Bạn đã kinh doanh trong ngành hàng này bao lâu rồi</li>
                <li>Bạn kinh doanh ngành hàng online được bao lâu</li>
                <li>Đội ngũ của bạn gồm những ai</li>
                <li>Thông tin liên hệ</li>
                <li>Liên kết đến các trang mạng xã hội (Twitter, Facebook)</li>
            </ul>
            <p class="mb-8">
                Bạn có thể chỉnh sửa hoặc xoá bài viết này tại <b>đây</b> hoặc thêm
                những bài viết mới trong phần quản lý <b>Trang nội dung</b>.
            </p>
            <button
                class="transition ease-in-out delay-150 bg-blue-500 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300 px-5 py-2">
                XEM VIDEO
            </button>
        </div>
    </div>

    <div class="bg-[url('/img/bg-gt01.jpg')] md:h-[346px] h-[650px] w-full bg-cover bg-no-repeat  mb-20">
        <div class="w-full h-full bg-black bg-opacity-80 flex justify-center items-center text-center ">
            <div class="flex md:flex-row flex-col gap-7 md:mx-10">
                <div class="w-full text-white">
                    <div class="flex justify-center mb-3">
                        <img src="/img/icon_support_1.png" alt="" />
                    </div>
                    <div class="mb-3 text-xl">
                        <h3>Hỗ trợ</h3>
                    </div>
                    <div class="px-5">
                        <p>
                            Chúng tôi luôn hỗ trợ trực tuyến 24/7. Hãy liên hệ với chúng tôi
                            để giải đáp thắc mắc.
                        </p>
                    </div>
                </div>
                <div class="w-full text-white">
                    <div class="flex justify-center mb-3">
                        <img src="/img/icon_support_2.png" alt="" />
                    </div>
                    <div class="mb-3 text-xl">
                        <h3>Liên hệ</h3>
                    </div>
                    <div class="px-5">
                        <p>
                            Liên hệ đường dây nóng hoặc gửi mail vào hộp thư của chúng tôi nếu bạn có bất cứ đề nghị hay
                            thắc mắc gì.
                        </p>
                    </div>
                </div>
                <div class="w-full text-white">
                    <div class="flex justify-center mb-3">
                        <img src="/img/icon_support_3.png" alt="" />
                    </div>
                    <div class="mb-3 text-xl">
                        <h3>Đối tác</h3>
                    </div>
                    <div class="px-5">
                        <p>
                            TP Group rất vui khi được hợp tác cùng các bạn. Hãy liên lạc với chúng tôi nếu các bạn có ý định
                            cộng tác nhé.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="2xl:mx-32 mx-auto mb-20">
        <div class="uppercase text-3xl font-extralight text-center mb-10">
            Gặp gỡ nhân viên của chúng ta
        </div>
        <div class="flex lg:flex-row flex-wrap gap-6 h-auto w-auto">
            <div class="w-[390px] h-[460px] flex justify-center items-center relative mx-auto">
                <div class="absolute top-0">
                    <img class="h-[351px] w-[351px]" src="/img/member-1.jpg" alt="">
                </div>
                <div class="absolute w-[304px] h-[131px] bottom-0 bg-white border-2 border-black">
                    <div class="w-full text-center h-auto py-2">
                        <div class="uppercase text-xs font-semibold mb-4">
                            Melanie martinez
                        </div>
                        <div class="text-slate-400 mb-5">
                            Kiến trúc sư
                        </div>
                        <div class=" flex justify-center gap-1">
                            <div class="h-[34px] w-[34px] border-2 border-black flex justify-center items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor"
                                    viewBox="0 0 24 24">
                                    <path
                                        d="M12 0c-6.628 0-12 5.373-12 12s5.372 12 12 12 12-5.373 12-12-5.372-12-12-12zm9.885 11.441c-2.575-.422-4.943-.445-7.103-.073-.244-.563-.497-1.125-.767-1.68 2.31-1 4.165-2.358 5.548-4.082 1.35 1.594 2.197 3.619 2.322 5.835zm-3.842-7.282c-1.205 1.554-2.868 2.783-4.986 3.68-1.016-1.861-2.178-3.676-3.488-5.438.779-.197 1.591-.314 2.431-.314 2.275 0 4.368.779 6.043 2.072zm-10.516-.993c1.331 1.742 2.511 3.538 3.537 5.381-2.43.715-5.331 1.082-8.684 1.105.692-2.835 2.601-5.193 5.147-6.486zm-5.44 8.834l.013-.256c3.849-.005 7.169-.448 9.95-1.322.233.475.456.952.67 1.432-3.38 1.057-6.165 3.222-8.337 6.48-1.432-1.719-2.296-3.927-2.296-6.334zm3.829 7.81c1.969-3.088 4.482-5.098 7.598-6.027.928 2.42 1.609 4.91 2.043 7.46-3.349 1.291-6.953.666-9.641-1.433zm11.586.43c-.438-2.353-1.08-4.653-1.92-6.897 1.876-.265 3.94-.196 6.199.196-.437 2.786-2.028 5.192-4.279 6.701z" />
                                </svg>
                            </div>
                            <div class="h-[34px] w-[34px] border-2 border-black flex justify-center items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor"
                                    viewBox="0 0 24 24">
                                    <path
                                        d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z" />
                                </svg>
                            </div>
                            <div class="h-[34px] w-[34px] border-2 border-black flex justify-center items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor"
                                    viewBox="0 0 24 24">
                                    <path
                                        d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z" />
                                </svg>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="w-[390px] h-[460px] flex justify-center items-center relative mx-auto">
                <div class="absolute top-0">
                    <img class="h-[351px] w-[351px]" src="/img/member-2.jpg" alt="">
                </div>
                <div class="absolute w-[304px] h-[131px] bottom-0 bg-white border-2 border-black">
                    <div class="w-full text-center h-auto py-2">
                        <div class="uppercase text-xs font-semibold mb-4">
                            Jackson martinez
                        </div>
                        <div class="text-slate-400 mb-5">
                            Kiến sư xây dựng
                        </div>
                        <div class=" flex justify-center gap-1">
                            <div class="h-[34px] w-[34px] border-2 border-black flex justify-center items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor"
                                    viewBox="0 0 24 24">
                                    <path
                                        d="M12 0c-6.628 0-12 5.373-12 12s5.372 12 12 12 12-5.373 12-12-5.372-12-12-12zm9.885 11.441c-2.575-.422-4.943-.445-7.103-.073-.244-.563-.497-1.125-.767-1.68 2.31-1 4.165-2.358 5.548-4.082 1.35 1.594 2.197 3.619 2.322 5.835zm-3.842-7.282c-1.205 1.554-2.868 2.783-4.986 3.68-1.016-1.861-2.178-3.676-3.488-5.438.779-.197 1.591-.314 2.431-.314 2.275 0 4.368.779 6.043 2.072zm-10.516-.993c1.331 1.742 2.511 3.538 3.537 5.381-2.43.715-5.331 1.082-8.684 1.105.692-2.835 2.601-5.193 5.147-6.486zm-5.44 8.834l.013-.256c3.849-.005 7.169-.448 9.95-1.322.233.475.456.952.67 1.432-3.38 1.057-6.165 3.222-8.337 6.48-1.432-1.719-2.296-3.927-2.296-6.334zm3.829 7.81c1.969-3.088 4.482-5.098 7.598-6.027.928 2.42 1.609 4.91 2.043 7.46-3.349 1.291-6.953.666-9.641-1.433zm11.586.43c-.438-2.353-1.08-4.653-1.92-6.897 1.876-.265 3.94-.196 6.199.196-.437 2.786-2.028 5.192-4.279 6.701z" />
                                </svg>
                            </div>
                            <div class="h-[34px] w-[34px] border-2 border-black flex justify-center items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor"
                                    viewBox="0 0 24 24">
                                    <path
                                        d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z" />
                                </svg>
                            </div>
                            <div class="h-[34px] w-[34px] border-2 border-black flex justify-center items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor"
                                    viewBox="0 0 24 24">
                                    <path
                                        d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z" />
                                </svg>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="w-[390px] h-[460px] flex justify-center items-center relative mx-auto">
                <div class="absolute top-0">
                    <img class="h-[351px] w-[351px]" src="/img/member-3.jpg" alt="">
                </div>
                <div class="absolute w-[304px] h-[131px] bottom-0 bg-white border-2 border-black">
                    <div class="w-full text-center h-auto py-2">
                        <div class="uppercase text-xs font-semibold mb-4">
                            janis joblin
                        </div>
                        <div class="text-slate-400 mb-5">
                            Nhà thiết kế nội thất
                        </div>
                        <div class=" flex justify-center gap-1">
                            <div class="h-[34px] w-[34px] border-2 border-black flex justify-center items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor"
                                    viewBox="0 0 24 24">
                                    <path
                                        d="M12 0c-6.628 0-12 5.373-12 12s5.372 12 12 12 12-5.373 12-12-5.372-12-12-12zm9.885 11.441c-2.575-.422-4.943-.445-7.103-.073-.244-.563-.497-1.125-.767-1.68 2.31-1 4.165-2.358 5.548-4.082 1.35 1.594 2.197 3.619 2.322 5.835zm-3.842-7.282c-1.205 1.554-2.868 2.783-4.986 3.68-1.016-1.861-2.178-3.676-3.488-5.438.779-.197 1.591-.314 2.431-.314 2.275 0 4.368.779 6.043 2.072zm-10.516-.993c1.331 1.742 2.511 3.538 3.537 5.381-2.43.715-5.331 1.082-8.684 1.105.692-2.835 2.601-5.193 5.147-6.486zm-5.44 8.834l.013-.256c3.849-.005 7.169-.448 9.95-1.322.233.475.456.952.67 1.432-3.38 1.057-6.165 3.222-8.337 6.48-1.432-1.719-2.296-3.927-2.296-6.334zm3.829 7.81c1.969-3.088 4.482-5.098 7.598-6.027.928 2.42 1.609 4.91 2.043 7.46-3.349 1.291-6.953.666-9.641-1.433zm11.586.43c-.438-2.353-1.08-4.653-1.92-6.897 1.876-.265 3.94-.196 6.199.196-.437 2.786-2.028 5.192-4.279 6.701z" />
                                </svg>
                            </div>
                            <div class="h-[34px] w-[34px] border-2 border-black flex justify-center items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor"
                                    viewBox="0 0 24 24">
                                    <path
                                        d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z" />
                                </svg>
                            </div>
                            <div class="h-[34px] w-[34px] border-2 border-black flex justify-center items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="currentColor"
                                    viewBox="0 0 24 24">
                                    <path
                                        d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z" />
                                </svg>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <div class="mb-36 bg-[url('/img/counter-about.jpg')] w-full md:h-[273px] h-[520px] bg-center">
        <div class="w-full h-full flex md:flex-row flex-col justify-around items-center text-center text-white">
            <div class="w-auto h-auto">
                <div class="text-5xl font-medium">
                    321
                </div>
                <div>
                    Dự án hoàn thành
                </div>
            </div>
            <div class="w-auto h-auto">
                <div class="text-5xl font-medium">
                    27
                </div>
                <div>
                    Công trình
                </div>
            </div>
            <div class="w-auto h-auto">
                <div class="text-5xl font-medium">
                    125
                </div>
                <div>
                    Giải thưởng
                </div>
            </div>
            <div class="w-auto h-auto">
                <div class="text-5xl font-medium">
                    483
                </div>
                <div>
                    Khách thân quen
                </div>
            </div>
        </div>
    </div>

    <p class="mb-20 2xl:ml-40 ml-10">Copyright © 2023 Pixel Company. Powered by Haravan.</p>
</template>

<script setup>

</script>

<style scoped>

</style>

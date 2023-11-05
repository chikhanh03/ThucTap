<template>
    <Disclosure as="nav" v-slot="{ open }" class="sticky top-0 bg-white border-b-2">
    <div class="mx-auto px-2 max-w-7xl sm:px-6 lg:px-2">
      <div class="relative flex h-20 items-center justify-between">
        <div class="absolute inset-y-0 left-0 flex items-center sm:hidden">
          <!-- Mobile menu button-->
          <DisclosureButton class="relative inline-flex items-center justify-center rounded-md p-2 text-gray-400 hover:bg-gray-700
             hover:text-white focus:outline-none focus:ring-2 focus:ring-inset focus:ring-white">
            <span class="absolute -inset-0.5" />
            <span class="sr-only">Open main menu</span>
            <Bars3Icon v-if="!open" class="block h-6 w-6" aria-hidden="true" />
            <XMarkIcon v-else class="block h-6 w-6" aria-hidden="true" />
          </DisclosureButton>
        </div>
        <div class="flex flex-1 items-center justify-center sm:items-stretch sm:justify-start">
          <div class="flex flex-shrink-0 items-center">
            <a href="/"><img class="h-8 w-auto" src="https://theme.hstatic.net/1000122243/1000533602/14/logo.png?v=45"
              alt="Your Company" /></a>
          </div>
          <div class="hidden lg:flex xl:ml-32 mx-auto sm:ml-6 sm:block">
            <div class="flex lg:space-x-4">
              <a class="hover-menu" v-for="item in navigation" :key="item.name" :href="item.href" :class="[item.current ? 'text-white' : 'text-gray-500',
                'rounded-md px-3 py-2 text-sm font-medium']" :aria-current="item.current ? 'page' : undefined">{{
                item.name }}</a>
            </div>
          </div>
        </div>
        <div class="hidden absolute inset-y-0 right-0 md:flex items-center pr-2 md:static md:inset-auto md:ml-6 md:pr-0">
          <p>Hotline: 0123456789</p>
        </div>
      </div>
    </div>

    <DisclosurePanel class="sm:hidden ">
      <div class="space-y-1 px-2 pb-3 pt-2">
        <DisclosureButton v-for="item in navigation" :key="item.name" as="a" :href="item.href" :class="[item.current ? 'bg-gray-900 text-white' : 'text-gray-300 hover:bg-gray-700 hover:text-white',
          'block rounded-md px-3 py-2 text-base font-medium']" :aria-current="item.current ? 'page' : undefined">{{
    item.name }}</DisclosureButton>
      </div>
    </DisclosurePanel>
  </Disclosure>

  <div class="mx-auto p-4">
    <slot />
  </div>
</template>

<style scoped>
.fixed-menu {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  background-color: white;
  /* Màu nền của menu */
  z-index: 999;
  /* Đảm bảo menu hiển thị trên các phần tử khác */
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  /* Hiển thị đổ bóng cho menu nếu cần */
  /* Thêm các thuộc tính CSS khác tùy theo thiết kế của bạn */
}
</style>
<script setup>
import { Disclosure, DisclosureButton, DisclosurePanel, Menu, MenuButton, MenuItem, MenuItems } from '@headlessui/vue'
import { Bars3Icon, BellIcon, XMarkIcon } from '@heroicons/vue/24/outline'

const navigation = [
  { name: 'TRANG CHỦ', href: '/', current: false },
  { name: 'GIỚI THIỆU', href: '/about', current: false },
  { name: 'TIN TỨC - SỰ KIỆN', href: '/news-events', current: false },
  { name: 'THƯ VIỆN ẢNH', href: '/photo-library', current: false },
  { name: 'LIÊN HỆ', href: '/contact', current: false },
]
</script>
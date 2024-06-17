<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar>
      <template #logo>
        <NavbarLogo link="https://www.google.com/" alt="Flowbite logo" image-url="https://th.bing.com/th/id/OIP.D5Bmc2SVsk7fAnImJVPZRQHaHa?pid=ImgDet&rs=1">
          SENA JULIANTI
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">Home</NavbarLink>
          
        </NavbarCollapse>
      </template>
    </Navbar>
    <div class="px-4 mx-auto max-w-screen-xl text-center py-5 lg:py-5">
    <img src="./assets/img/halo.png">
    </div><br>
    
<section class="bg-white dark:bg-dark-900">
    <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16 grid lg:grid-cols-2 gap-8 lg:gap-16">
        <div class="flex flex-col justify-center">
            <h1 class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-dark-900 md:text-5xl lg:text-6xl dark:text-white">Tentang Saya</h1>
            <p class="mb-8 text-lg font-normal text-dark-500 lg:text-xl dark:text-dark-400">Halo nama saya Sena Julianti, lulusan Smk Assalaam Bandung dengan Jurusan Rekayasa Perangkat Lunak.
                Mempunyai kepribadian yang Tangguh, Disiplin, Mandiri dan mampu bekerja secara tim maupun individu.Selain itu, saya juga menyukai Desain dan senang belajar hal-hal baru.
            </p>          
        </div>
        <div>
            <img class="mx-auto w-full lg:max-w-xl h-60 rounded-lg sm:h-96 shadow-xl" src="./assets/img/ttng-sena.png"  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
        </div>
    </div>
</section>

<!-- biodata -->
<div class="px-4 mx-auto max-w-screen-xl text-center py-5 lg:py-5">
    <img src="./assets/img/datadiri.png">
    </div><br> <br>

    <!-- contact -->    
    <center>
<a href="#" class="block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700">
  <img src="https://th.bing.com/th/id/R.4215d06a0ba187367801890e0b26f79d?rik=kBeXD76aimx9eg&riu=http%3a%2f%2fcdn.onlinewebfonts.com%2fsvg%2fimg_386133.png&ehk=uQjI6mpqwp8ApclPDI6CTp8vVmrKHcRGiUDF0EHiAUs%3d&risl=&pid=ImgRaw&r=0" style="width: 200px;">
  <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"></h5>
    <p class="font-normal text-gray-700 dark:text-gray-400"></p>
    <div>
      <table>
        <tr>
            <td>Whatsapp</td>
            <td>:</td>
            <td><a href="https://api.whatsapp.com/send?phone=+6289631729799&text=Halo">Sena julianti</a></td>
        </tr>
        <tr>
            <td>Instagram</td>
            <td>:</td>
            <td><a href="https://instagram.com/senajulianti?igshid=MzNlNGNkZWQ4Mg==" class="hover:underline">@senajulianti</a></td>
        </tr>
        <tr>
            <td>Github</td>
            <td>:</td>
            <td><a href="https://github.com/senajlnti" class="hover:underline ">senajlnti</a></td>
        </tr>


      </table>
    </div>
</a>
</center>
</template>

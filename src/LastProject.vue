<template>
    <div class="container mx-auto">
        <div class="text-center">
            <b class="p-2" style="font-size: 30px; color: rgb(27, 27, 71); font-family: 'sans-serif', Calibri, 'Trebuchet MS', sans-serif;">
                PROJECT TERAKHIR
            </b>
            <div style="width: 30%; background: rgb(27, 27, 71); height: 5px; margin: auto;"></div>
        </div>
        <br>
        <div class="grid grid-cols-1 md:grid-cols-3 lg:grid-cols-4 gap-4">
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/lastproject1.png" alt="Juara 1 Lomba Musikalisasi Puisi">
                <div class="overlay-text">
                    <p>Login Untuk Admin</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/lastproject2.png" alt="Seni Tari Saman">
                <div class="overlay-text">
                    <p>Halaman Dashboard Admin</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/lastproject3.png" alt="Seni Tari Tradisional">
                <div class="overlay-text">
                    <p>Tentang Kami</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/last4.png" alt="Memainkan Alat Musik Tradisional">
                <div class="overlay-text">
                    <p>Kategori Produk</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/last5.png" alt="Praktik Kerja Industri di PT Khatulistiwa Nusantara Indonesia">
                <div class="overlay-text">
                    <p>Halaman Home Untuk User</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/last6.png" alt="Juara 2 karate">
                <div class="overlay-text">
                    <p>Kategori Produk</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/last7.png" alt="Seni Tari Saman">
                <div class="overlay-text">
                    <p>Halaman Produk</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/last7.png" alt="Memainkan Alat Musik Tradisional">
                <div class="overlay-text">
                    <p>Halaman Produk</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/last8.png" alt="Memainkan Alat Musik Tradisional">
                <div class="overlay-text">
                    <p>Daftar Kategri Produk</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/last9.png" alt="Seni Menggambar">
                <div class="overlay-text">
                    <p>Halaman Produk Sesuai Kategori</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/last10.png" alt="Bermain Panah">
                <div class="overlay-text">
                    <p>Halaman Detail Produk</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/last11.png" alt="Membuat Aplikasi Website Sederhana">
                <div class="overlay-text">
                    <p>Halaman Kontak Kami</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Gallery'
};
</script>

<style scoped>
.image-container {
    position: relative;
    overflow: hidden;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.overlay-text {
    position: absolute;
    top: 50%; /* Menengahkan secara vertikal */
    left: 50%; /* Menengahkan secara horizontal */
    transform: translate(-50%, -50%);
    background-color: rgba(0, 0, 0, 0.7);
    color: white;
    text-align: center;
    opacity: 0; /* Awalnya transparan */
    transition: opacity 0.3s ease; /* Animasi perubahan opacity */
    display: flex;
    align-items: center; /* Menengahkan teks secara vertikal */
    justify-content: center; /* Menengahkan teks secara horizontal */
    width: 100%; /* Memastikan teks mengisi seluruh area parent */
    height: 100%; /* Memastikan teks mengisi seluruh area parent */
}

.image-container:hover .overlay-text {
    opacity: 1; /* Tampilkan teks saat gambar dihover */
}

.grid {
    margin-top: 20px;
}

@media (min-width: 768px) {
    .grid-cols-2 {
        grid-template-columns: repeat(2, minmax(0, 1fr));
    }
}

@media (min-width: 1024px) {
    .grid-cols-3 {
        grid-template-columns: repeat(3, minmax(0, 1fr));
    }
}

@media (min-width: 1280px) {
    .grid-cols-4 {
        grid-template-columns: repeat(4, minmax(0, 1fr));
    }
}
</style>


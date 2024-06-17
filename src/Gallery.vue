<template>
    <div class="container mx-auto">
        <div class="text-center">
            <b class="p-2" style="font-size: 30px; color: rgb(27, 27, 71); font-family: 'sans-serif', Calibri, 'Trebuchet MS', sans-serif;">
                SEMUA GALLERY
            </b>
            <div style="width: 30%; background: rgb(27, 27, 71); height: 5px; margin: auto;"></div>
        </div>
        <br>
        <div class="grid grid-cols-1 md:grid-cols-3 lg:grid-cols-4 gap-4">
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/lomba1.jpg" alt="Juara 1 Lomba Musikalisasi Puisi">
                <div class="overlay-text">
                    <p>Juara 1 Lomba Musikalisasi Puisi</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/pengalaman2.jpg" alt="Seni Tari Saman">
                <div class="overlay-text">
                    <p>Seni Tari Saman</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/pengalaman3.jpg" alt="Seni Tari Tradisional">
                <div class="overlay-text">
                    <p>Seni Tari Tradisional</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/pengalaman4.jpg" alt="Memainkan Alat Musik Tradisional">
                <div class="overlay-text">
                    <p>Memainkan Alat Musik Tradisional</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/coding3.jpg" alt="Praktik Kerja Industri di PT Khatulistiwa Nusantara Indonesia">
                <div class="overlay-text">
                    <p>Praktik Kerja Industri di PT Khatulistiwa Nusantara Indonesia</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/sertifikat.jpg" alt="Juara 2 karate">
                <div class="overlay-text">
                    <p>Juara 2 karate</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/saman1.jpg" alt="Seni Tari Saman">
                <div class="overlay-text">
                    <p>Seni Tari Saman</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/pengalaman4.jpg" alt="Memainkan Alat Musik Tradisional">
                <div class="overlay-text">
                    <p>Memainkan Alat Musik Tradisional</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/saman1.jpg" alt="Memainkan Alat Musik Tradisional">
                <div class="overlay-text">
                    <p>Memainkan Alat Musik Tradisional</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/menggambar.jpg" alt="Seni Menggambar">
                <div class="overlay-text">
                    <p>Seni Menggambar</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/panah.jpg" alt="Bermain Panah">
                <div class="overlay-text">
                    <p>Bermain Panah</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/coding3.jpg" alt="Membuat Aplikasi Website Sederhana">
                <div class="overlay-text">
                    <p>Membuat Aplikasi Website Sederhana</p>
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


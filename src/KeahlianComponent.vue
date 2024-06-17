<template>
    <div class="container mx-auto">
        <center>
            <b class="p-2"
                style="font-size: 30px; text-align: center; color: rgb(27, 27, 71); font-family: 'sans-serif', Calibri, 'Trebuchet MS', sans-serif;">
                GALLERY KEAHLIAN
            </b>
            <center>
                <div style="width: 30%; background: rgb(27, 27, 71); height: 5px;"></div>
            </center>
            <br>
            <center>
                <h1> <span style="font-family: sans-serif; font-size: 20px; text-align: center; margin: 10px;"> </span>
                    &nbsp; <b style="font-size: 25px; color: blue;">
                    </b> </h1> <br> 
            </center>
        </center>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/pengalaman4.jpg" alt="">
                <div class="overlay-text">
                    <p>Memainkan Alat Musik Tradisional</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/saman1.jpg" alt="">
                <div class="overlay-text">
                    <p>Memainkan Alat Musik Tradisional</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/menggambar.jpg" alt="">
                <div class="overlay-text">
                    <p>Seni Menggambar</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/panah.jpg" alt="">
                <div class="overlay-text">
                    <p>Bermain Panah</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/coding3.jpg" alt="">
                <div class="overlay-text">
                    <p>Membuat Aplikasi Website Sederhana</p>
                </div>
            </div>
            <div class="image-container">
                <img class="h-auto max-w-full rounded-lg" src="./assets/img/pengalaman2.jpg" alt="">
                <div class="overlay-text">
                    <p>Seni Tari Saman</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.image-container {
    position: relative;
    overflow: hidden;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.overlay-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: rgba(0, 0, 0, 0.7);
    color: white;
    text-align: center;
    opacity: 0;
    transition: opacity 0.3s ease;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 100%;
}

.image-container:hover .overlay-text {
    opacity: 1;
}

.grid {
    margin-top: 20px;
}

@media (min-width: 768px) {
    .md\:grid-cols-3 {
        grid-template-columns: repeat(3, minmax(0, 1fr));
    }
}
</style>

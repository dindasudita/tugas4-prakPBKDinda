<template>
    <div class="fitur" id="Features">
        <h1>FITUR-FITUR TAS</h1>
        <p>Tas pada umumnya memiliki berbagai fitur yang dirancang untuk memenuhi kebutuhan pengguna dalam membawa barang-barang mereka secara aman, nyaman, dan terorganisir. Beberapa fitur umum yang dimiliki oleh tas adalah:</p>
        <div class="fitur-list">
            <div class="fitur-item">
                <h2>Zipper</h2>
                <img src="../assets/resleting.jpeg" alt="Resleting">
                <p>Zipper digunakan untuk menjaga barang-barang di dalam tas tetap aman dan terlindungi.</p>
            </div>
            <div class="fitur-item">
                <h2>Kantong</h2>
                <img src="../assets/kantong.jpeg" alt="Kantong">
                <p>Kantong tambahan membantu dalam mengorganisir barang-barang kecil agar mudah diakses.</p>
            </div>
            <div class="fitur-item">
                <h2>Waterproof</h2>
                <img src="../assets/Waterproof.jpg" alt="Waterproof">
                <p>Tas tahan air atau waterproof melindungi barang-barang di dalamnya dari basah.</p>
            </div>
            <div class="fitur-item">
                <h2>Strap</h2>
                <img src="../assets/strap.jpeg" alt="Strap">
                <p>Strap yang kuat dan nyaman membantu pengguna untuk membawa tas dengan nyaman.</p>
            </div>
        </div>
    </div>
</template>

<script setup>
</script>

<style scoped>
#Features{
    scroll-margin-top: 80px;
}

.fitur {
    text-align: center;
    padding: 20px;
    color:#3c0f0e;
    border: 3px solid #f4c9b4;
    border-radius: 25px;
    margin-top: 20px;
    padding-bottom: 100px;
}

.fitur h1 {
    font-size: 24px;
    margin-bottom: 10px;
}

.fitur p {
    color: #3c0f0e;
    margin-bottom: 20px;
}

.fitur-list {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.fitur-item {
    flex: 0 0 200px;
    margin: 10px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    background-color: #f4c9b4;
}

.fitur-item img {
    max-width: 100px;
    margin-bottom: 10px;
}

.fitur-item h2 {
    font-size: 18px;
    margin-bottom: 5px;
}

.fitur-item p {
    font-size: 14px;
    color: #3c0f0e;
}
</style>

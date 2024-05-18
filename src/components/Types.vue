<template>
    <div class="tipe" id="Types">
        <h1>Jenis Tas</h1>
        <p>Berikut adalah 5 jenis tas yang cukup populer dan umum dilihat dan silahkan klik gambar untuk mengetahui kelebihan dan kekurangan tiap jenis tas</p>
        <ul>
            <li>
                <h3>Backpack</h3>
                <p>Backpack dapat diartikan sebagai tas yang memiliki strap untuk digunakan saat membawa tas di belakang tubuh. Jadi, keberadaan strap yang terpasang berguna untuk memikul atau menggendong tas di punggung.
                    Strap-nya juga tidak hanya satu melainkan dua sehingga pas dengan pundak. Di kalangan masyarakat, kata backpack sendiri sangat identik dengan petualangan, perjalanan sederhana, liburan, serta kebebasan. 
                    Alasannya karena tas backpack memiliki kapasitas memuat barang yang besar juga terdiri dari berbagai kompartemen. Penggunaannya yang bisa dibawa di belakang punggung sangat memudahkan mobilitas penggunanya. <br>
                    (((Klik gambar untuk mengetahui kelebihan dan kekurangan tas😀)))
                </p>
                <img src="../assets/backpack.jpeg" alt="Backpack" @click="showDetails('Backpack')" />
                <div v-if="selectedType === 'Backpack'">
                    <h4>Kelebihan:</h4>
                    <p>Praktis dibawa saat bepergian jauh, nyaman dipakai di punggung, muat banyak barang.</p>
                    <h4>Kekurangan:</h4>
                    <p>Berat jika terlalu banyak barang, kurang formal untuk acara formal.</p>
                </div>
            </li><br>
            <li>
                <h3>Totebag</h3>
                <p>
                    Totebag merupakan salah satu model tas jinjing yang terbuka di bagian atas kemudian dilengkapi dengan dua tali pendek yang berfungsi untuk menjinjing atau menggantungkan tasnya di pundak.
                    Umumnya, tote bag hanya punya satu bukaan utama untuk memasukkan atau mengeluarkan barang, memudahkan penggunanya dalam hal pemakaian. 
                    Bentuk yang saat ini sedang sering terlihat di pasaran adalah persegi panjang dengan tinggi kantong lebih besar dari lebarnya. <br>
                    (((Klik gambar untuk mengetahui kelebihan dan kekurangan tas😀)))
                </p>
                <img src="../assets/BtoteBag.jpeg" alt="Totebag" @click="showDetails('Totebag')" />
                <div v-if="selectedType === 'Totebag'">
                    <h4>Kelebihan:</h4>
                    <p>
                        Muat banyak barang, cocok untuk belanja, desain simpel dan stylish.
                    </p>
                    <h4>Kekurangan:</h4>
                    <p>
                        Kadang tidak memiliki resleting atau penutup, kurang cocok untuk barang berharga.
                    </p>
                </div>
            </li><br>
            <li>
                <h3>Hand Bag</h3>
                <p>
                    Hand bag, atau yang sering disebut juga sebagai tas tangan, adalah jenis tas yang dirancang untuk dibawa dengan tangan atau di bawah lengan.
                    Hand bag biasanya memiliki ukuran yang lebih kecil daripada tas yang dikenakan di bahu atau di punggung, sehingga cocok untuk membawa barang-barang penting seperti ponsel, dompet, kunci, dan barang kecil lainnya. Hand bag tersedia dalam berbagai desain, bahan, dan warna yang dapat disesuaikan dengan gaya dan kebutuhan penggunanya.
                    Beberapa hand bag juga dilengkapi dengan tali panjang yang dapat dilepas, sehingga dapat digunakan sebagai tas bahu atau crossbody bag untuk meningkatkan fleksibilitas dalam penggunaannya. <br>
                    (((Klik gambar untuk mengetahui kelebihan dan kekurangan tas😀)))
                </p>
                <img src="../assets/HandBag.jpeg" alt="Handbag" @click="showDetails('Handbag')">
                <div v-if="selectedType === 'Handbag'">
                    <h4>Kelebihan:</h4>
                    <p>
                        Terlihat elegan dan cocok untuk acara formal.
                    </p>
                    <h4>Kekurangan:</h4>
                    <p>
                        Harus dipegang setiap waktu dan kapasitas terbatas
                    </p>
                </div>
            </li><br>
            <li>
                <h3>Shoulder Bag</h3>
                <p>
                    Shoulder bag adalah tas yang cara pakainya adalah dengan cara diselempangkan di salah satu sisi pundak atau bahu.
                    Tas ini memiliki beberapa kompartemen yang dapat dipakai untuk menampung barang baik kecil maupun besar sesuai kebutuhan pemakainya.
                    Ada yang bisa dipakai pada tampilan kasual, ada pula yang cocok dipakai saat Anda bergaya semi formal. <br>
                    (((Klik gambar untuk mengetahui kelebihan dan kekurangan tas😀)))
                </p>
                <img src="../assets/shoulderBag.jpeg" alt="Shoulderbag" @click="showDetails('Shoulderbag')">
                <div v-if="selectedType === 'Shoulderbag'">
                    <h4>Kelebihan:</h4>
                    <p>
                        Nyaman dipakai sehari-hari dan memiliki ruang penyimpanan yang besar.
                    </p>
                    <h4>Kekurangan:</h4>
                    <p>
                        Membebani satu bahu pemakai tas.
                    </p>
                </div>
            </li><br>
            <li>
                <h3>Clutch</h3>
                <p>
                    Clutch adalah jenis tas yang sangat populer karena kemampuannya untuk menambah sentuhan glamor pada penampilan. Tas ini biasanya berbentuk kotak atau persegi panjang dengan desain yang minimalis dan elegan. 
                    Clutch biasanya tidak memiliki tali, sehingga harus dipegang dengan tangan atau dijepit di bawah lengan. Meskipun kapasitas penyimpanannya terbatas, clutch seringkali cukup besar untuk menampung ponsel, kunci, kartu identitas, dan barang penting lainnya.
                    Tas ini sangat cocok digunakan untuk acara-acara formal atau malam karena memberikan kesan mewah dan eksklusif. <br>
                    (((Klik gambar untuk mengetahui kelebihan dan kekurangan tas😀)))
                </p>
                <img src="../assets/clutch.jpeg" alt="clutch" @click="showDetails('clutch')">
                <div v-if="selectedType === 'clutch'">
                    <h4>Kelebihan:</h4>
                    <p>
                        Tampilan modis dan ringan.
                    </p>
                    <h4>Kekurangan:</h4>
                    <p>
                        Kapasitas terbatas dan harus dipegang setiap saat.
                    </p>
                </div>
            </li><br>
        </ul>
    </div>
</template>

<script setup>
    import { ref } from 'vue';

    const selectedType = ref(null);

    function showDetails(type) {
        if (selectedType === type) {
            selectedType.value = null;
        } else {
            selectedType.value = type;
        }
    }
</script>

<style scoped>
#Types{
    scroll-margin-top: 80px;
}

.tipe {
        padding: 20px;
        background-color: #fae5da;
        border: 3px solid #f4c9b4;
        border-radius: 25px;
        margin-top: 20px;
        color: #3c0f0e;
}

ul {
        list-style-type: none;
        padding: 0;
}

li {
        margin-bottom: 20px;
}

img {
        max-width: 50%;
        max-height: auto;
        border-radius: 5px;
        cursor: pointer;
}

div {
        margin-top: 10px;
}
</style>

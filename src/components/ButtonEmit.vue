<template>
    <div class="sejarah" id="#History">
        <br>
        <button class="btn" @click="sejarahTas">
            <h2>Sejarah Tas</h2>
        </button><br><br>
    </div>
    
</template>

<script setup>
const emit=defineEmits(['response'])

function sejarahTas(){
    emit(
        'response', 
        'Tas pertama kali muncul pada abad ke-14 oleh bangsa Mesir dengan model tas pinggang. Kemudian pada abad ke 16 diciptakannya model tas jinjing atau yang lebih dikenal dengan naman Handbag. Lalu, abad ke 17 mulai muncul model-model tas fashionable, dimana kemunculannya ini diandai dengan banyaknya model tas yang memiliki ukuran kecil. Desain tas yang berkembang pada abad ini yakni tas dengan hiasan sulaman yang biasanya dipakai untuk ke acara pernikahan.'
        )
}
</script>

<style scoped>
#History{
    scroll-margin-top: 80px;
}
.btn {
  padding: 10px 20px;
  background-color: #eda484; 
  color: #3c0f0e;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.btn:hover {
  background-color: #e57652; 
}
</style>
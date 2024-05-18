<template>
  <div>
    <header>
      <Navbar />
    </header>
    <Home />
    <div class="emit">
    <Title title="Emit" />
    
    <Emitcom @response="sejarahTas" />
    {{ childMsg }}
    </div>

    <Features />
    <Types />
    <footer>
      <Slot >
        Anda berada di halaman terakhir, terima kasih banyak atas waktu yang anda sisihkan untuk membaca tulisan saya.
      </Slot>
    </footer>

  </div>
</template>

<script setup>
import { ref } from 'vue';
import Navbar from './components/Navbar.vue'
import Home from './components/Home.vue'
import Emitcom from './components/ButtonEmit.vue'



import Features from './components/Features.vue'
import Types from './components/Types.vue'
import Slot from './components/Slot.vue';
const childMsg = ref('Sejarah tas')

function sejarahTas(msg){
  childMsg.value = msg
  alert('Silahkan cek sejarah tas')
}
</script>

<style >
@import url("https://fonts.googleapis.com/css2?family=Rubik:wght@300;400;500;600;700;800&display=swap");
  
body{
  background-color: #fae5da;
}
header {
  padding-bottom: 100px;
}

.content {
  margin-top: 20px;
}
</style>
<!DOCTYPE html>
<html>
<meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/>

  <link rel="icon" type="image/svg+xml" href="https://feeldreams.github.io/main-icon.png"> 
  <link rel="apple-touch-icon" href="https://feeldreams.github.io/main-icon.png">
  
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Caveat&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@400;700&display=swap" rel="stylesheet">
  
  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
  <script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script>
  <script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script><link href="https://feeldreams.github.io/maukahkamu/style.css" rel="stylesheet" type="text/css" />
  <script src="https://unpkg.com/scrollreveal"></script>
  
<head>
<title>SELAMAT ANNIVERSERY SAYANG</title>
</head>
<body>
	
   <div class="overlay">
     <!-- Teks Loading --><div class="loading-message">Hai kamu!<br>Tunggu dulu ya..</div>
   </div>
   
   <!-- Ganti Audio di Sini, edit url di dalam src -->
   <audio src="https://feeldreams.github.io/maukahkamu/seandainya.mp3" id="linkmp3" class="sembunyi"></audio>
   
   <!-- Pesan Pertama -->
   <section class="first">
       <!-- Background --><div class="wp"><img id="imgsatu" src="https://feeldreams.github.io/maukahkamu/wpsatu.jpg"/></div>
       <!-- Stiker --><img id="first_stiker" class="stiker fade-in" src="https://feeldreams.github.io/bunga.gif"/>
       
       <h1 class="title">SELAMAT ANNIV SAYANG</h1>
       <p class="flip">KAMU SAYANG GA</p>
       <p class="slide-up">JANGAN LUPA</p>
  </section>
  
  <!-- Pesan Kedua -->
  <section>
      <!-- Background --><div class="wp"><img id="imgdua" src="https://feeldreams.github.io/maukahkamu/wpdua.jpg"/></div>
      <!-- Stiker --><img class="stiker fade-in" src="https://feeldreams.github.io/pusn.gif"/>
      
      <h2 class="title">Pesan Judul</h2>
      <p class="slide-right">Pesan Deskripsi</p>
  </section>
  
  <!-- Pesan Ketiga dengan Animasi Ngetik -->
  <section>
  	<!-- Background --><div class="wp"><img id="imgtiga" src="https://feeldreams.github.io/maukahkamu/wptiga.jpg"/></div>
      <p id="teksnimasi">Pesan Teks Animasi Ngetik</p>
  </section>
  
  <!-- Pesan Keempat dengan Pertanyaan -->
  <section>
  	<!-- Background --><div class="wp"><img id="imgempat" src="https://feeldreams.github.io/maukahkamu/wpempat.jpg"/></div>
      <!-- Stiker --><img class="stiker fade-in" src="https://feeldreams.github.io/bunga.gif"/>
      
      <h2 class="title">Pesan Judul</h2>
      <p class="bold slide-right">Pesan Pertanyaan</p>
      
      <div id="Tombol">
       <a id="By" onClick="fungsipertama()">Tombol Fungsi Pertama</a>
       <a id="Bn" onClick="fungsikedua()">Tombol Fungsi Kedua</a>
     </div>
  </section>
  
  <!-- Pesan Akhir, edit di paling bawah di dalam Script -->
  <section id="iniakhir">
  	<!-- Background --><div class="wp" id="wpakhir"><img src="https://feeldreams.github.io/maukahkamu/wplima.jpg"/></div>
      <!-- Stiker --><img id="stikerakhir" class="stiker fade-in" src="https://feeldreams.github.io/g5.gif"/>
      
      <img id="stikerakhir2" style="display:none" src="https://feeldreams.github.io/emawh.gif"/>
      <h1 id="judulakhir"></h1>
      <p id="kalimatakhir"></p>
      <p id="palingakhir"></p>
      <div id="TombolWA">
        <a onClick="menuju()">Balas </a>
      </div>
  </section>
  
  <div id="initom" class="menu">
  <a class='tombol' onclick="tes()">
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-down" viewBox="0 0 16 16"> <path fill-rule="evenodd" d="M8 1a.5.5 0 0 1 .5.5v11.793l3.146-3.147a.5.5 0 0 1 .708.708l-4 4a.5.5 0 0 1-.708 0l-4-4a.5.5 0 0 1 .708-.708L7.5 13.293V1.5A.5.5 0 0 1 8 1z"/> </svg>
  </a>
  </div>

<script>
// Teks ketika klik tombol Mau
function fungsipertama(){
       fungsi=0;tes();
       teksjudulakhir = "TESTETETETTE";
       tekskalimatakhir = "GUDANG FOREVER";
}

// Teks ketika klik tombol Gamau
function fungsikedua(){
       fungsi=0;tes();
       teksjudulakhir = "";
       tekskalimatakhir = "";
}

// Teks Akhir
teksjudulakhir2 = "";
tekspalingakhir = "";
  
// Teks yang akan dikirim ke WhatsApp
pesanwhatsapp = "";

const body = document.querySelector("body"); initom.style="opacity:0;bottom:0;transition:none"; audio = new Audio('' + linkmp3.src); function berjatuhan() {const heart = document.createElement("div"); heart.className = "fas fa-heart"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-heart"); if (heartArr.length > 100) {heartArr[0].remove()}},100);
</script>
<script src="https://feeldreams.github.io/maukahkamu/main.js"></script>
</body>
</html>

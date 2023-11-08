# Membuat Game 2D Platformer dengan Konsep Mirip Super Mario Bros
<br>Mata Kuliah 	: Dasar Pemrograman
<br> Nama		: Denis Firmansyah
<br>NIM		:	1227050034
<br>Jurusan		: [Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Intro
Pada kesempatan kali ini saya ingin membahas mengenai pembuatan game berbasis 2D Platformer. Kita akan membuat game sederhana dimana player dapat menggerakkan karakter dan menyerang musuh.

## Analisis : Pengenalan
Semakin maraknya dunia digital saat ini, salah satu di antaranya ada suatu program yang biasa dinikmati oleh semua kalangan usia, baik itu usia muda, remaja, maupun dewasa. Program yang tersebut diciptakan untuk menghibur, mengedukasi, atau bahkan memberikan sensasi yang berbagai macam. Program yang diciptakan tersebut biasa disebut sebagai *game* atau 'permainan'. Dalam laman ini, saya akan membahas proyek yang akan/telah saya buat yang bertemakan 2D Platformer.

## Analisis : Branding
Pada tahap ini kita mengeksplorasi *branding* dari sistem yang dibuat. *Branding* meliputi:
- Merk : **Sword and Traps** 
- Tagline : Melawan musuh dan menghindari jebakan
- Campaign : Bagaimana membuat game yang membuat playernya berpikir cermat untuk menangani tantangan yang diberikan
- Target user :
  - Usia 7+ 
  - Seseorang yang memiliki sikap sabar yang lumayan tinggi
  - Seseorang yang senang mengeksplorasi game 2 dimensi
  - Seseorang yang senang dengan tantangan
- User experience theme :
  - Mudah
  - Sederhana
  - Sedikit memancing emosi
  - Dapat diselesaikan dengan 10 menit bermain
  - Warna : suasana zaman pertengahan
 
## Analisis : User Story
Pada tahap ini kita mengeksplorasi kebutuhan para pemain untuk kenyamanan dalam bermain.

|Sebagai|Saya ingin bisa|Sehingga|Prioritas
|---|---|---|---|
|Player|Bergerak ke samping|Bisa mencapai tempat yang dituju|⭐⭐⭐⭐⭐|
|Player|Menyerang musuh|Bisa meminimalisir tantangan|⭐⭐⭐⭐|
|Player|Melompat|Bisa melewati rintangan yang diberikan|⭐⭐⭐⭐⭐|

## Analisis : Struktur Data
Di tahap ini kita mengeksplorasi kinerja dari beberapa bagian penting yang ada pada game yang dibuat
Aspek-aspek penting yang ada pada game :
- Player menyerang Musuh
- Musuh menyerang Player
- Player menghindari Jebakan
- Jebakan memberi luka Player

## Design : User Experience (UX) Design
![sample sword and traps](https://github.com/DenisFirmansyah/Produk-Teknologi-Informasi/assets/121292416/5eae1f65-cc7e-4bb7-850c-51c19fef3be6)
- Pada tahap ini kita mengeksplorasi alur interaksi player saat memainkan game pada setiap kondisi.
- Ada banyak kondisi yang dapat ditemui oleh player mulai dari menyerang musuh, terkena damage oleh musuh atau jebakan, hingga mati akibat serangan berlebih dari musuh atau jebakan.
- Desain yang dibuat di atas adalah *low fidelity design* dimana kualitas desainnya paling sederhana tapi cepat untuk dibuat.

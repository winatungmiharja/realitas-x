---
layout: default
---

# Tugas 2 - Mencoba Aplikasi AR

<div style='display:flex;justify-content: center;background-color : #5b7f98; border-radius: 1em; margin-bottom:1em; overflow : hidden'>
    <img src='https://github.com/winatungmiharja/realitas-x/assets/64743796/4189991d-700c-49e7-9e7c-7f505da5fc7a' 
    width='100%'/>
</div>

## Piano Vision

Aplikasi ini merupakan aplikasi berbasis _Augmented Reality_ yang memungkinkan kita untuk bermain dan berlatih piano dengan menggunakan VR. Beberapa fitur utama yang dimiliki diantaranya :

- Bermain piano tanpa piano
- Berlatih bermain piano
- Bermain musik dengan piano
- Membangun _feeling_ yang kuat dengan piano

## Background

Sebelumnya, bisa dibilang saya termasuk orang yang sudah tidak asing dengan musik, saya seringnya main gitar dan tidak mahir bermain piano

Untuk basic skill piano, sebelumnya saya sudah bisa bermain chord-chord dasar dan chord-chord jazz, serta sedikit melodi. Namun kala itu keyboard saya dijual. Alhasil karena sudah lama ngga main, bisa dibilang _muscle memory_ dan memori dari otak saya nya sudah hilang juga hehehe.

Apakah aplikasi ini bisa mengembalikan knowledge tersebut? Mari kita lihat 👌🏻

## Bermain piano tanpa piano

Ya, seperti kedenagrannya, aplikasi ini memungkinkan kita untuk bermain piano tanpa piano yang asli. Meskipun aplikasi ini juga menyediakan opsi untuk bermain dengan piano yang asli, namun disini saya mencoba fitur bermain tanpa piano

Fitur ini mengandalkan _hand tracking_ dan _pass thorugh_ dari oculus untuk mentranslasikan gerakan tengan kita ke tuts-tuts yang ditekan di piano, dimana tuts ini ditampilkan secara augmented ke _pass through_ kita. Namun di ss saya kelihatannya hitam saja, itu sebenarnya lingkungan sekitar saya.

Interaksi aplikasi ini sepenuhnya menggunakan tangan dan **tanpa controller**. Sebelum memulai bermain, kita melakukan _setup_ terlebih dahulu. Disini kita diminta untuk :

- Menentukan lebar piano
- Menentukan berapa banyak tuts
- Menentukan letak dan ketinggian piano

<div style='display:flex;justify-content: center;padding-bottom: 1em'>
    <img src='https://github.com/winatungmiharja/realitas-x/assets/64743796/f4e1412b-5815-4222-b035-78ca0127bcf1' 
    width='50%' style='border: 1px solid #DDDDDD; padding: 0.75em'/>
</div>

Setelah setup kita pun diberikan window "Adjuster" yang memungkinkan kita untuk setup-setup lagi jika dirasa masih ada hal yang kurang. Adjuster ini juga bisa digunakan untuk melakukan setup window yang akan muncul nantinya.

Setelah setup kita bisa free play layaknya piano biasa, dan kita juga bisa memilih untuk latihan atau bermain lagu.

## Berlatih bermain piano

Kalau biasanya kita pemula ketika bermain piano itu ada namanya belajar _fingering_, jadi pada dasarnya kita belajar jari apa yang harus dipakai untuk menekan tuts dan juga penggunaan dan transisi jari-jari tersebut. Mungkin sketsa nya seperti ini

<div style='display:flex;justify-content: center;padding-bottom: 1em'>
    <img src='https://github.com/winatungmiharja/realitas-x/assets/64743796/2eb7c8f2-0424-484b-a995-131f3f9e5a6f' 
    width='50%' style='border: 1px solid #DDDDDD; padding: 0.75em'/>
</div>

Ya, jadi untuk latihan yang diberikan aplikasi ini sebenarnya adalah latihan fingering tersebut, dengan pilihan scale yang beragam

https://github.com/winatungmiharja/realitas-x/assets/64743796/71690e5d-610c-451b-b4cd-99e5bdb6ff6

Bisa dilihat jari-jari saya yang sudah usang dan kaku agak kesusahan menekan tuts nya, terlebih saya tidak bisa merasakan permukaannya benda dan juga hand tracking yang kadang suka cari gara-gara membuat saya sangat kesusahan untuk menyelesaikan misi sederhana ini

Selain itu, untuk latihan chord sebenarnya tidak ada course khusus layaknya misal chord c itu (1-3-5) karena pada dasarnya chord itu variasinya sangat banyak. Jadi untuk chord, mereka mengandalkan kita untuk membuat variasi sendiri dari scale yang sudah kita gunakan dari latihan, atau kita bisa lihat chord nya ketika kita ingin latihan sebuah lagu.

## Bermain musik dengan piano

Pada bagian ini kita bisa memilih musik dengan berbagai level, dimana level 1-4 fokusnya ke familiarisasi dan level 5 keatas sudah ada chord-chord nya. Pilihan lagunya tidak diragukan sangat banyak. dan kita bisa import lagu kita sendiri (format MIDI ini bisa diunduh di banyak website), dan dimainkan juga.

<div style='display:flex;justify-content: center;padding-bottom: 1em'>
    <img src='https://github.com/winatungmiharja/realitas-x/assets/64743796/675fd6b9-9af4-4dee-aa14-f4ba27445674' 
    width='50%' style='border: 1px solid #DDDDDD; padding: 0.75em'/>
</div>

https://github.com/winatungmiharja/realitas-x/assets/64743796/03b22e1e-80af-4046-bd3e-02e42732001b

di bagian bawah juga kita dikasi semacam toolbar untuk mengaktifkan metronome, kecepan main, temp, dan sebagainya

<div style='display:flex;justify-content: center;padding-bottom: 1em'>
    <img src='https://github.com/winatungmiharja/realitas-x/assets/64743796/285581d7-4c92-4408-9db1-d1f6b1c90947' 
    width='50%' style='border: 1px solid #DDDDDD; padding: 0.75em'/>
</div>

## Membangun _feeling_ yang kuat dengan piano

Tujuan dari aplikasi piano vision ini salah satunya yaitu membangun _muscle memory_ di jari2 kita sehingga kita bisa bermain piano dengan lebih seamless. Tau kan orang-orang yang bisa bermain piano sambil merem dan nangis, nah itu dia kuncinya. Hal itu bisa dicapai dengan berlatih terus menerus dan membangun memori untuk nada-nadanya sendiri. Ya, gak ada orang yang baru main piano sekali langsung tau semua nada dan melodi untuk Für Elise kan ya :)

Untuk menghadapi hal ini, Piano Vision memberikan fitur namanya **Memory Engine**. Disini kita akan berlatih dua tahap

- memainkan lagu yang dipilih hanya 1 tangan secara berulang-ulang

https://github.com/winatungmiharja/realitas-x/assets/64743796/ed16d6d5-85bd-416e-b9fa-8a25fa0dadd9

- memainkan lagu yang petunjuk bar nya dihilangkan

https://github.com/winatungmiharja/realitas-x/assets/64743796/ba083f00-ee99-449a-88b0-90f443325375

## Review

### Interaksi

interaksi aplikasi ini sangat mudah dipahami, apalagi karena tidak menggunakkan controller dan interaksi dengan UI layaknya seperti menekan layar di virtual environment saja. Namun bisa dibilang, untuk hand tracking yang dipakai bisa dibilang masih 50 persen dari yang saya suka.

### Grafik dan Visual

Untuk visual dan grafik bisa dibilang sangat enak dipandang, modern, sederhana, sehingga pengguna yang baru membuka aplikasi bisa memahami fungsi dan cara kerja aplikasi ini _right off the bat_.

Cuman kalau dibandingkan dengan game musik kayak osu, visual effect nya bisa dibilang masih kurang, kalau sama aplikasi musik di hp mungkin yang tau namanya deemo, visual nya bisa dibilang 11 12. Boleh dicatat kalau aplikasi ini fokusnya lebih ke edukasi ketimbang entertainment ya.

### Musik

Selain library musik yang banyak dan bisa juga import music dari ekxternal. Aplikasi ini tidak cocok bagi temen-temen yang mau _freestyling_ main chord-chord manis ditengah hujan dan senja. Sebenarnya lumayan akurat ya tracking nya ketika memainkan lagu yang sudah ada, namun ketika freestyling akurasi ini jadi rendah. Dari mau _healing_ jadi _hurting_ 😓😓

# Kesimpulan

Sayangnya untuk review kali ini saya tidak memiliki keyboard fisik yang bisa disambungin, kalau ada tentunya akan tambah seru ya, Tapi sejauh ini bisa dibilang "Piano Vision" adalah aplikasi AR yang menawarkan pengalaman unik bermain piano. Apakah dengan menggunakan aplikasi ini _muscle memory_ saya yang hilang jadi kembali? bisa dibilang kembali 10%. Saya rasa aplikasi ini membuat belajar piano itu kurva nya gak se 'steep' itu, dan belajar piano sebenarnya jadi lebih mudah.

# Mobile Guide

## Theme
You'll need to meet high expectations for quality and funcionality <br/>
#### Three primary themes:
- Clarity
- Deference
- Depth

#### Interface Essentials:
- Bars
- Views
- Controls


## App Architecture
##### Launching
- Menyediakan layar peluncuran 
- Peluncuran dalam orientasi yang sesuai 
- Hindari meminta informasi setup depan 
- Hindari menampilkan perjanjian lisensi dalam aplikasi dan penafian 
- Kembalikan keadaan sebelumnya ketika restart aplikasi Anda 
- Jangan mendorong reboot 
- Hindari meminta orang untuk menilai aplikasi Anda terlalu cepat atau terlalu sering

#### Onboarding
- Menyediakan orientasi yang membantu orang menikmati aplikasi Anda, bukan hanya mengaturnya 
- Dapatkan untuk tindakan cepat 
- Mengantisipasi kebutuhan akan bantuan 
- Tetap berpegang pada hal-hal penting dalam tutorial 
- Membuat belajar menyenangkan dan ditemukan

#### Loading
- Jelaskan saat pemuatan terjadi 
- Tampilkan konten sesegera mungkin 
- Mendidik atau menghibur orang untuk menutupi waktu pemuatan

#### Modality
- Gunakan modalitas ketika masuk akal 
- Alert cadangan untuk memberikan penting, idealnya ditindaklanjuti dan informasi 
- Jaga agar tugas modal tetap sederhana, pendek, dan terfokus secara sempit 
- Pertimbangkan untuk menggunakan gaya modal fullscreen untuk konten mendalam atau tugas yang kompleks 
- Selalu menyertakan tombol yang menolak tampilan modal 
- Bila perlu, membantu orang menghindari kehilangan data dengan mendapatkan konfirmasi sebelum menutup tampilan modal 
- Buatlah mudah untuk mengidentifikasi tugas tampilan modal itu 
- Mengkoordinasikan tampilan tampilan modal dengan aplikasi Anda 
- Pilih gaya transisi modal yang masuk akal di aplikasi Anda

#### Navigation Type
- Hierarchical Navigation
- Flat Navigation
- Content-Driven

#### Navigation Tips
- Selalu berikan jalan yang jelas 
- Desain struktur informasi yang membuatnya cepat dan mudah untuk mendapatkan konten 
- Gunakan gerakan sentuh untuk menciptakan fluiditas 
- Gunakan komponen navigasi standar 
- Gunakan bilah navigasi untuk melintasi hierarki data 
- Gunakan tab bar untuk menyajikan Kategori rekan konten atau fungsi 
- Di iPad, gunakan tampilan terpisah alih-alih bilah tab 
- Gunakan kontrol Halaman ketika Anda memiliki beberapa halaman dari jenis konten yang sama

#### Accesing User Data and Resources
- Minta izin hanya ketika aplikasi Anda jelas membutuhkan akses ke data atau sumber daya 
- Minta izin saat peluncuran hanya ketika data atau sumber daya diperlukan agar aplikasi Anda berfungsi 
- Menulis salinan yang jelas menggambarkan bagaimana aplikasi Anda menggunakan data atau sumber daya yang Anda minta

#### Settings
- Menyimpulkan apa yang Anda dapat dari sistem 
- Serius memprioritaskan opsi konfigurasi dalam aplikasi Anda 
- Paparan opsi konfigurasi jarang berubah dalam pengaturan 
- Menyediakan cara pintas ke Pengaturan saat yang tepat


## Visual Design
#### Adaptivity and Layout

#### Auto Layout
Dengan menggunakan Auto Layout, Anda dapat menentukan aturan (dikenal sebagai batasan) yang mengatur konten di aplikasi Anda.
- Menggunakan Auto Layout, Anda dapat menentukan aturan (dikenal sebagai kendala) yang mengatur konten dalam aplikasi Anda 
- Area aman menentukan area dalam tampilan yang tidak tercakup oleh navigation bar, tab bar, toolbar, atau tampilan lain yang mungkin disediakan oleh pengontrol tampilan
- Patuhi area aman yang ditentukan sistem dan margin tata letak

#### Auto Layout Size Classes
A view may possess any combination of size classes: 
- Regular width, regular height 
- Compact width, compact height 
- Regular width, compact height 
- Compact width, regular height

#### General Layout Considerations
- Pastikan bahwa konten utama jelas pada ukuran default 
- Menjaga penampilan yang konsisten secara keseluruhan di seluruh aplikasi Anda 
- Gunakan berat visual dan keseimbangan untuk menyampaikan pentingnya 
- Gunakan keselarasan untuk memudahkan pemindaian dan untuk berkomunikasi organisasi dan hirarki 
- Jika memungkinkan, dukung orientasi potret dan lanskap 
- Bersiaplah untuk perubahan ukuran teks 
- Memberikan target sentuhan yang cukup untuk elemen interaktif 
- Preview aplikasi Anda pada beberapa perangkat 
- Terapkan margin keterbacaan saat menampilkan teks pada perangkat yang lebih besar

#### Animation
- Gunakan animasi dan efek gerak bijaksana
- Berjuang untuk realisme dan kredibilitas
- Gunakan animasi yang konsisten 
- Membuat animasi opsional

#### Branding
- Menggabungkan branding yang halus dan tidak mencolok 
- Jangan biarkan branding mendapatkan di jalan desain aplikasi besar 
- Menunda konten melalui branding 
- Tahan godaan untuk menampilkan logo Anda di seluruh aplikasi Anda 
- Patuhi pedoman merek dagang Apple

#### Color
- Jangan hanya mengandalkan warna untuk membedakan antara objek atau mengkomunikasikan informasi penting 
- Gunakan warna bijaksana untuk komunikasi 
- Pertimbangkan memilih palet warna terbatas yang berkoordinasi dengan logo aplikasi Anda 
- Pertimbangkan memilih warna untuk menunjukkan interaktivitas seluruh aplikasi Anda 
- Berikan dua versi warna aksen Anda untuk memastikannya terlihat bagus dalam mode terang dan gelap 
- Hindari menggunakan warna yang sama untuk elemen interaktif dan noninteractive 
- Pertimbangkan bagaimana karya seni dan tembus mempengaruhi warna terdekat 
- Uji skema warna aplikasi Anda di bawah berbagai kondisi pencahayaan 
- Pertimbangkan bagaimana True Tone efek tampilan warna 
- Pertimbangkan bagaimana penggunaan warna mungkin dirasakan di negara-negara lain dan budaya 
- Hindari menggunakan warna yang dapat menyulitkan orang untuk memahami konten di aplikasi Anda

#### Dark Mode
- Mematuhi mode penampilan yang dipilih orang dalam pengaturan 
- Uji desain Anda dalam penampilan terang dan gelap 
- Pastikan konten Anda tetap terbaca dengan nyaman dalam Mode Gelap saat Anda menyesuaikan pengaturan aksesibilitas kontras dan transparansi

#### Launch Screen
- Desain layar peluncuran yang hampir identik dengan layar pertama aplikasi Anda 
- Hindari termasuk teks pada layar peluncuran Anda 
- Mengecilkan peluncuran 
- Jangan beriklan

#### Terminology
- Gunakan akrab, kata-kata dimengerti dan frase 
- Jauhkan teks antarmuka yang jelas dan ringkas 
- Identifikasi elemen interaktif dengan tepat 
- Hindari bahasa yang mungkin terdengar menggurui 
- Berusaha keras untuk nada informal dan ramah 
- Hati-hati saat menggunakan humor 
- Gunakan bahasa dan citra yang relevan dan konsisten 
- Lihat Tanggal akurat

#### Typography for IOS
#### Video
- Result of padding a 4:3 video, in full-screen viewing mode
- Result of padding a 21:9 video, in fit to screen viewing mode


## Icons and Images
Supply high-resolution images for all artwork in your app, for all devices your app supports.
- Ksederhanaan 
- Memberikan titik fokus tunggal 
- Desain ikon dikenali 
- Jaga agar latar belakang tetap sederhana dan hindari transparansi 
- Gunakan kata-kata hanya ketika mereka penting atau bagian dari logo 
- Jangan menyertakan foto, screenshot, atau elemen antarmuka 
- Jangan gunakan replika Produk Perangkat Keras Apple 
- Jangan menempatkan ikon aplikasi Anda di seluruh antarmuka 
- Uji ikon Anda terhadap wallpaper yang berbeda 
- Jauhkan ikon sudut persegi (untuk IOS)

## Bars
#### Navigation Bars
#### Search Bars
#### Sidebars
#### Status Bars
#### Tab Bars


## Views

## Controls

## Extensions

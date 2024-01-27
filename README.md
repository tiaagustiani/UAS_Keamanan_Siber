# UAS_Keamanan_Siber
**Tia Agustiani**<br>
**I.2111730**<br>
**Sabtu 27 Januari 2024**<br>==========================================================================================

## **No.1 (Forward proxy vs Reverse proxy)**
***Forward proxy*** menangani lalu lintas klien, mengatur dan mengamankannya. Sebaliknya, ***reverse proxy*** melindungi server dengan menangani permintaan klien, memastikan mereka mencapai server yang tepat, dan mengembalikan hasilnya kepada klien, yang tidak sadar akan keterlibatan langsung server.

## **No.2 (Metasploit)** <br>
Metasploit merupakan *framework* yang membantu selama proses pentesting.<br> Metasploit berisi modul 
*exploit* dan *scanner* dari *vulnerability* yang sudah ditemukan dan 
*dipublish*. Dengan Metasploit, kita dapat membuat *payload* dan 
mengirimnya ke komputer atau server target.

# **No.3 (Firewall vs IDS vs IPS)** <br>
### **Firewall:**

*   Fungsi Utama firewall adalah sebagai penghalang digital yang mengawasi serta mengelola aliran data antara jaringan pribadi dan jaringan umum.
*   Firewall melakukan analisis terhadap paket data yang masuk dan keluar dari jaringan, lalu memutuskan apakah harus mengizinkan atau memblokirnya berdasarkan aturan keamanan yang telah diatur.

*   Dalam mode stateful, firewall memantau status koneksi dan mengambil keputusan untuk mengizinkan atau memblokir berdasarkan konteks koneksi tersebut.
<br>

### **Intrusion Detection System (IDS):**

*   IDS berfokus pada pengidentifikasian aktivitas yang mencurigakan atau potensi serangan di dalam jaringan.
*   IDS melakukan analisis terhadap lalu lintas jaringan dan mencermati log kejadian untuk mengenali pola atau perilaku yang mencurigakan.

*   IDS memberikan peringatan atau notifikasi ketika mendeteksi aktivitas yang mencurigakan, tanpa melakukan tindakan pencegahan otomatis.
 <br>

### **Intrusion Prevention System (IPS):**

*   IPS tidak hanya mendeteksi serangan seperti yang dilakukan oleh IDS, tetapi juga mengambil langkah-langkah aktif untuk mencegah atau memblokir serangan tersebut.
*   IPS beroperasi dengan cara serupa dengan IDS, namun memiliki kemampuan untuk secara otomatis memblokir atau menanggapi serangan yang terdeteksi.
*   IPS dapat merespon secara otomatis dengan memblokir alamat IP atau jenis serangan tertentu, sesuai dengan kebijakan keamanan yang telah ditetapkan.

# **No.4 (GDPR & PDP)** <br>

### **GDPR**
***General Data Protection Regulation*** (GDPR) atau Regulasi Perlindungan Data Umum, adalah ketentuan perlindungan data yang diimplementasikan di Uni Eropa. Kebijakan ini mulai berlaku pada 25 Mei 2018 dan didesain untuk memberikan kendali lebih besar kepada individu terkait data pribadi mereka, sambil meningkatkan standar keamanan dan perlindungan data di seluruh wilayah Uni Eropa.

Beberapa aspek utama dalam GDPR melibatkan hak individu untuk mengetahui bagaimana informasi pribadi mereka dikumpulkan, diproses, dan disimpan. Perusahaan dan organisasi yang mengumpulkan atau mengelola data pribadi diharuskan untuk mematuhi prinsip-prinsip GDPR, yang mencakup persetujuan yang jelas, pemrosesan data yang adil dan terbatas, serta perlindungan yang kuat terhadap risiko kebocoran atau kehilangan data.

Pelanggaran terhadap ketentuan GDPR dapat dikenai sanksi yang serius, termasuk denda yang signifikan. Oleh karena itu, dampak GDPR terasa besar terutama pada pendekatan perusahaan dan organisasi dalam mengelola dan menjaga keamanan data pribadi.<br><br>

### **PDP**
PDP (*Personal Data Protection*) atau "Perlindungan Data Pribadi", adalah istilah yang mengacu pada inisiatif menjaga kerahasiaan informasi pribadi individu. Hal ini sering terkait dengan kebijakan, peraturan, atau undang-undang yang bertujuan untuk melindungi privasi dan keamanan data pribadi seseorang.

Secara umum, usaha perlindungan data pribadi ini mencakup:


*   Pengumpulan Data yang Adil dan Terbuka: Penyedia layanan atau organisasi harus mengumpulkan data pribadi dengan cara yang adil dan memberikan informasi yang jelas kepada individu mengenai cara penggunaan data mereka.
*   Persetujuan: Organisasi perlu memperoleh izin atau persetujuan dari individu sebelum mengumpulkan atau memproses data pribadi mereka.
*   Keamanan Data: Perlindungan data melibatkan langkah-langkah keamanan yang kokoh untuk mencegah akses yang tidak sah, kebocoran, atau penggunaan yang tidak sah terhadap data pribadi.
*   Akses dan Kendali: Secara umum, individu memiliki hak untuk mengakses data pribadi mereka dan mengendalikan bagaimana data tersebut digunakan.
*   Pelaporan Pelanggaran Keamanan Data: Jika terjadi pelanggaran keamanan data, diharapkan bahwa organisasi melaporkannya sesuai dengan ketentuan hukum yang berlaku.

Peraturan seperti *General Data Protection Regulation* (GDPR) adalah contoh regulasi yang dirancang untuk melindungi data pribadi individu. Maksud utama dari upaya perlindungan data pribadi adalah untuk menciptakan suasana di mana individu merasa yakin dalam memberikan informasi pribadi tanpa khawatir akan penyalahgunaan atau pelanggaran privasi.

# **No.5 (OWASP)** <br>

Beberapa alasan yang membuat OWASP dijadikan acuan dalam konteks keamanan perangkat lunak yaitu:

1. OWASP secara berkala merilis proyek-proyek dan panduan yang terkait dengan kerentanan dan solusi keamanan terkini. Ini mencakup pedoman praktis, metode pengujian, dan daftar kerentanan yang sering dihadapi.

2. OWASP mengembangkan Kerangka Keamanan Aplikasi Web (Application Security Verification Standard - ASVS), standar industri untuk mengukur tingkat keamanan aplikasi web. ASVS memberikan petunjuk yang jelas untuk menilai tingkat keamanan aplikasi.

3. Setiap beberapa tahun, OWASP merilis daftar 10 risiko keamanan aplikasi web teratas. Ini memberikan wawasan berharga tentang ancaman keamanan paling mendesak dan umum dihadapi oleh aplikasi web.

4. OWASP adalah komunitas terbuka yang mengundang partisipasi dari para ahli keamanan, pengembang perangkat lunak, dan pihak terkait. Keterlibatan komunitas dalam penyusunan panduan dan proyek-proyek OWASP memberikan legitimasi dan akurasi yang tinggi.

5. Panduan dan proyek-proyek OWASP difokuskan pada praktik terbaik dalam mengidentifikasi, mencegah, dan merespons terhadap ancaman keamanan perangkat lunak. Ini membantu organisasi untuk menerapkan pendekatan yang efektif dalam pengembangan dan pengujian keamanan aplikasi mereka.

Dengan menggunakan panduan dan proyek-proyek OWASP sebagai acuan, pengembang perangkat lunak dapat meningkatkan keamanan aplikasi mereka dan mengurangi risiko terhadap serangan keamanan.

# **No.6**
### **Link:** https://www.credly.com/badges/848a3344-ec5c-4ab6-ba3e-725db2734bcd/public_url

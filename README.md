# RENCANA PEMBELAJARAN SEMESTER (RPS)
**BERBASIS OUTCOME-BASED EDUCATION (OBE)**

**Institusi:** Universitas Muhammadiyah Pontianak  
**Program Studi:** S1 Informatika  
**Mata Kuliah:** Komputasi Awan (*Cloud Computing*)  
**Bobot SKS:** 3 SKS (3 Teori)  
**Semester:** Ganjil / Genap  
**Rumpun Mata Kuliah:** Sistem Jaringan Cerdas / Rekayasa Perangkat Lunak  
**Prasyarat:** Jaringan Komputer, Sistem Operasi

---

## 1. Deskripsi Mata Kuliah
Mata kuliah ini memberikan pemahaman komprehensif, teoretis, dan analitis mengenai paradigma *Cloud Computing*. Berfokus pada aspek perancangan arsitektur, model layanan, teknologi fondasi (virtualisasi dan kontainerisasi), serta strategi migrasi. Mahasiswa akan mempelajari cara merancang topologi infrastruktur awan yang aman (*cloud security*), memiliki skalabilitas tinggi, dan hemat biaya (*cloud economics*). Pembahasan juga mencakup arsitektur modern seperti *Serverless*, *Microservices*, serta integrasi layanan komputasi awan dengan ekosistem ujung (*Edge Computing/IoT*) dan analitik data.

## 2. Capaian Pembelajaran Lulusan (CPL) yang Dibebankan
*   **CPL-1 (Sikap):** Menunjukkan sikap bertanggung jawab dan mematuhi standar etika serta kepatuhan hukum terkait privasi dan keamanan data pada infrastruktur komputasi terdistribusi.
*   **CPL-2 (Pengetahuan):** Menguasai konsep teoretis arsitektur jaringan, virtualisasi, sistem terdistribusi, dan prinsip dasar komputasi awan secara mendalam.
*   **CPL-3 (Keterampilan Umum):** Mampu menerapkan pemikiran logis, kritis, dan sistematis dalam mengevaluasi serta memilih solusi teknologi awan yang tepat sasaran untuk memecahkan masalah sistem informasi terintegrasi.
*   **CPL-4 (Keterampilan Khusus):** Mampu merancang, menganalisis, dan memodelkan arsitektur *Cloud Computing* (IaaS, PaaS, SaaS) yang *scalable*, aman, dan efisien secara ekonomi berdasarkan studi kasus kebutuhan industri atau penelitian.

## 3. Capaian Pembelajaran Mata Kuliah (CPMK)
*   **CPMK-1:** Mahasiswa mampu menjelaskan paradigma dasar, karakteristik, model layanan, dan model penyebaran *Cloud Computing* sesuai standar NIST.
*   **CPMK-2:** Mahasiswa mampu menganalisis teknologi fondasi awan yang mencakup arsitektur *Data Center*, mekanisme *Hypervisor* (Virtualisasi), dan *Containerization*.
*   **CPMK-3:** Mahasiswa mampu merancang arsitektur jaringan, komputasi, dan penyimpanan data terdistribusi berbasis *cloud* dengan menerapkan prinsip keamanan (IAM) dan *Load Balancing*.
*   **CPMK-4:** Mahasiswa mampu mengevaluasi aspek manajerial komputasi awan yang meliputi *Service Level Agreement* (SLA), optimasi biaya (*FinOps*), dan strategi migrasi sistem prapemrograman ke awan.
*   **CPMK-5:** Mahasiswa mampu merancang model topologi integrasi komputasi awan tingkat lanjut dengan *Edge-IoT Nodes* dan *Machine Learning Pipeline* melalui pendekatan studi kasus.

---

## 4. Rencana Kegiatan Pembelajaran Mingguan (16 Pertemuan)

*Catatan Waktu Beban Belajar SKS Teori: Tatap Muka (TM) 3x50 menit, Penugasan Terstruktur (PT) 3x60 menit, Belajar Mandiri (BM) 3x60 menit.*

| Minggu | Kemampuan Akhir yang Diharapkan (Sub-CPMK) | Materi Pembelajaran | Bentuk & Metode Pembelajaran | Penilaian (Indikator & Kriteria) | Bobot |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **1** | Mampu menjelaskan evolusi dan esensi Komputasi Awan. | 1. Evolusi Sistem Terdistribusi ke *Cloud*<br>2. Definisi & 5 Karakteristik Esensial NIST<br>3. Pemain utama penyedia layanan awan global | Kuliah Interaktif, Diskusi<br>*(TM: 3x50", PT: 3x60")* | Ketepatan menjelaskan konsep dasar dan pergeseran paradigma IT tradisional ke *cloud*. | 3% |
| **2** | Mampu membedakan model layanan komputasi awan. | 1. *Infrastructure as a Service* (IaaS)<br>2. *Platform as a Service* (PaaS)<br>3. *Software as a Service* (SaaS)<br>4. *Backend as a Service* (BaaS) | Kuliah, Studi Kasus Analisis Layanan<br>*(TM: 3x50", BM: 3x60")* | Ketepatan memetakan layanan komersial ke dalam kategori IaaS, PaaS, atau SaaS. | 3% |
| **3** | Mampu mengevaluasi model *deployment cloud* sesuai kebutuhan organisasi. | 1. *Public, Private, Hybrid, & Community Cloud*<br>2. Konsep *Multi-cloud Architecture*<br>3. Analisis *trade-off* (Biaya vs Kontrol) | Kuliah Interaktif, *Problem-based Learning*<br>*(TM: 3x50", PT: 3x60")* | Argumen kritis pemilihan model deployment berdasarkan skenario kasus fiktif. | 5% |
| **4** | Mampu menganalisis teknologi dasar virtualisasi perangkat keras. | 1. Konsep *Hypervisor* (Type 1 *Bare-metal* vs Type 2 *Hosted*)<br>2. Isolasi *Resource* (CPU, RAM, Network)<br>3. *Virtual Machine* (VM) vs Fisik | Kuliah Interaktif, Presentasi Kelompok<br>*(TM: 3x50", BM: 3x60")* | Kejelasan mendeskripsikan peran hypervisor dalam membagi sumber daya fisik. | 5% |
| **5** | Mampu membedakan arsitektur *Virtual Machine* dan *Containerization*. | 1. Arsitektur *Container* (Docker Engine)<br>2. Kelebihan dan keterbatasan *Container* vs VM<br>3. Pengantar Orkestrasi (Kubernetes/Swarm) secara arsitektural | Kuliah Interaktif, Diskusi Kelompok<br>*(TM: 3x50", PT: 3x60")* | Ketepatan membandingkan latensi, ukuran, dan portabilitas antara VM dan Container. | 7% |
| **6** | Mampu merancang topologi sumber daya komputasi dan penyimpanan awan. | 1. Konsep *Elastic Compute* dan *Auto-scaling*<br>2. Perbedaan *Block Storage, File Storage, & Object Storage*<br>3. Kasus Penggunaan (misal: S3 vs EBS) | Kuliah Interaktif, Perancangan Arsitektur<br>*(TM: 3x50", PT: 3x60")* | Diagram topologi alokasi storage yang tepat untuk tipe data terstruktur dan tak terstruktur. | 8% |
| **7** | Mampu menganalisis arsitektur jaringan *cloud* dan ketersediaan layanan. | 1. *Virtual Private Cloud* (VPC) & *Subnetting*<br>2. *Load Balancing* & *Content Delivery Network* (CDN)<br>3. Konsep *Availability Zones* & *Regions* | Kuliah Interaktif, Analisis Kasus<br>*(TM: 3x50", BM: 3x60")* | Pemahaman merancang perutean trafik untuk menghindari *single point of failure*. | 8% |
| **8** | **Evaluasi Tengah Semester (UTS)** | **Review Materi Minggu 1-7 & Ujian Tulis Analitis** | **Ujian Tulis** | **Penguasaan konsep, model layanan, virtualisasi, dan desain topologi dasar.** | **20%** |
| **9** | Mampu mengevaluasi implementasi *Database* dalam lingkungan komputasi awan. | 1. *Managed Database* (RDS)<br>2. *Cloud-native NoSQL* (DynamoDB / Firestore)<br>3. Skalabilitas *Database* (Replikasi & *Sharding*) | Kuliah Interaktif, *Case-based Learning*<br>*(TM: 3x50", PT: 3x60")* | Pemilihan basis data yang optimal untuk aplikasi skala tinggi berdasar studi kasus. | 5% |
| **10** | Mampu merancang sistem menggunakan pendekatan *Serverless Computing*. | 1. Evolusi ke *Function as a Service* (FaaS)<br>2. Arsitektur berbasis *Event-driven*<br>3. Keterbatasan *Serverless* (*Cold start, Vendor lock-in*) | Kuliah Interaktif, Presentasi Kelompok<br>*(TM: 3x50", PT: 3x60")* | Kemampuan memetakan alur bisnis menjadi pemicu *event* dan fungsi *serverless*. | 5% |
| **11** | Mampu menganalisis kerangka keamanan komputasi awan. | 1. *Shared Responsibility Model*<br>2. *Identity and Access Management* (IAM) & *Principle of Least Privilege*<br>3. Keamanan Data (Enkripsi *in-transit* & *at-rest*) | Kuliah Interaktif, Diskusi<br>*(TM: 3x50", BM: 3x60")* | Penyusunan kebijakan kontrol akses (IAM) yang sesuai standar keamanan operasional. | 7% |
| **12** | Mampu merencanakan strategi migrasi sistem ke lingkungan awan. | 1. *Cloud Adoption Framework*<br>2. Strategi Migrasi "The 6 R's" (*Rehost, Replatform, Refactor*, dll)<br>3. *Disaster Recovery Plan* (RTO & RPO) | Kuliah Interaktif, Perancangan Arsitektur<br>*(TM: 3x50", PT: 3x60")* | Penyusunan skenario migrasi yang paling minim risiko untuk server *on-premise* ke awan. | 7% |
| **13** | Mampu merancang arsitektur integrasi komputasi awan dengan *Edge AI* dan IoT. | 1. Pemisahan beban kerja: *Cloud Analytics* vs *Edge Inference*<br>2. Arsitektur *Message Broker* untuk jutaan *Node*<br>3. Pipa data *Machine Learning* di *Cloud* | Kuliah Pakar / Diskusi Mendalam<br>*(TM: 3x50", PT: 3x60")* | Kualitas desain diagram integrasi *Edge-to-Cloud* untuk akuisisi data sensor cerdas. | 7% |
| **14** | Mampu melakukan analisis ekonomi komputasi awan (*Cloud Economics*). | 1. *Total Cost of Ownership* (TCO)<br>2. Model *Pricing* (On-demand, Reserved, Spot)<br>3. Manajemen Keuangan *Cloud* (*FinOps*) | Kuliah Interaktif, Hitungan *Cost Calculator*<br>*(TM: 3x50", PT: 3x60")* | Keakuratan menghitung proyeksi penghematan biaya menggunakan *AWS/GCP Pricing Calculator*. | 5% |
| **15** | Desain Arsitektur *Cloud* Tingkat Lanjut. | Presentasi tugas akhir perancangan topologi awan yang terintegrasi, berskalabilitas tinggi, dan *cost-effective*. | Pembelajaran Berbasis Proyek (Review Dokumen)<br>*(TM: 3x50")* | Ketajaman analisis arsitektur, kelengkapan mitigasi risiko, dan justifikasi pemilihan layanan. | - |
| **16** | **Evaluasi Akhir Semester (UAS)** | **Review Dokumen Arsitektur & Studi Kasus Komprehensif** | **Evaluasi Proyek / Ujian Tulis** | **Komperehensifitas desain arsitektur, keamanan jaringan awan, dan efisiensi model deployment.** | **25%** |

---

## 5. Sistem Penilaian (OBE Assessment)

| Komponen Penilaian | Terkait dengan CPMK | Persentase Bobot | Keterangan |
| :--- | :--- | :--- | :--- |
| **Tugas Individu / Kuis Teori** | CPMK-1, CPMK-2, CPMK-4 | 20% | Pemahaman konseptual NIST, perbandingan VM vs Container, dan kalkulasi dasar FinOps. |
| **Tugas Kelompok (Analisis Kasus)** | CPMK-3, CPMK-4 | 25% | Makalah analisis strategi migrasi infrastruktur lokal ke awan dan perancangan IAM. |
| **Ujian Tengah Semester (UTS)** | CPMK-1, CPMK-2 | 20% | Ujian tertulis berfokus pada fondasi arsitektur, model layanan, dan virtualisasi. |
| **Dokumen Proyek Arsitektur Akhir (UAS)** | CPMK-3, CPMK-4, CPMK-5 | 35% | Evaluasi cetak biru (diagram topologi) solusi *Cloud* yang menyelesaikan masalah bisnis/penelitian, mencakup *load balancer*, *storage*, keamanan, integrasi ML/IoT, dan estimasi biaya (TCO). |
| **TOTAL** | | **100%** | |

## 6. Referensi & Daftar Pustaka

**Buku Utama:**
1. Erl, T., Puttini, R., & Mahmood, Z. (2013). *Cloud Computing: Concepts, Technology & Architecture*. Prentice Hall.
2. Buyya, R., Broberg, J., & Goscinski, A. M. (2011). *Cloud Computing: Principles and Paradigms*. John Wiley & Sons.
3. Kavis, A. K. (2014). *Architecting the Cloud: Design Decisions for Cloud Computing Service Models (SaaS, PaaS, and IaaS)*. Wiley.

**Buku/Dokumen Pendukung:**
1. Chou, K. (2020). *Cloud Native Architectures: Design high-availability and cost-effective applications for the cloud*. Packt Publishing.
2. *AWS Well-Architected Framework Documentation* (Whitepapers).
3. *Google Cloud Architecture Center: Reference Architectures*.

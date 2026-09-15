# Jawaban Soal STS - Version Control

**Nama:** Arya Nugraha  
**Kelas:** 12 PPLG 1  

---

### 1. Apa yang dimaksud dengan GitHub?
GitHub adalah platform berbasis cloud/web yang memanfaatkan sistem kontrol versi Git untuk menyimpan, mengelola, dan melacak perubahan kode sumber program, serta memfasilitasi kolaborasi antarpengembang perangkat lunak.

---

### 2. Fitur dan Komponen Utama GitHub
* **Repositories:** Ruang penyimpanan virtual untuk seluruh berkas proyek beserta riwayat revisinya.
* **Branches:** Cabang kerja terisolasi yang memungkinkan pengembang bekerja tanpa mengubah kode pada cabang utama.
* **Commits:** Catatan snapshot perubahan kode sumber yang disertai dengan pesan penjelas.
* **Pull Requests (PR):** Mekanisme usulan integrasi kode dari satu branch ke branch lain yang memfasilitasi proses tinjauan kode (*code review*).
* **Issues:** Sarana pencatatan bug, pelaporan masalah teknis, serta pengelolaan daftar tugas kerja tim.
* **GitHub Actions:** Fitur CI/CD bawaan untuk otomatisasi alur pengujian, build, dan deployment kode.

---

### 3. Alur Utama (GitHub Workflow)
* **Create a branch:** Membuat cabang baru yang berasal dari branch rujukan.
* **Make changes & Commit:** Melakukan modifikasi kode atau penambahan file, lalu menyimpan catatan perubahannya.
* **Create a Pull Request:** Membuka pull request agar rekan pengembang atau guru dapat meninjau kode.
* **Review & Feedback:** Menjalankan pengujian otomatis atau diskusi perbaikan jika ada koreksi.
* **Merge:** Menggabungkan kode dari branch kerja tersebut ke branch utama setelah disetujui.

---

### 4. Keuntungan Utama Pembatasan Branch main (Branch Protection)
* **Mencegah Kesalahan Langsung:** Menghindari commit atau penghapusan tidak disengaja langsung ke cabang utama/produksi.
* **Kontrol Kualitas Kode:** Memastikan seluruh perubahan wajib melewati tahap *code review* via Pull Request sebelum digabungkan.
* **Stabilitas Proyek:** Menjaga agar kode pada branch utama selalu stabil, teruji, dan bebas dari error dadakan.

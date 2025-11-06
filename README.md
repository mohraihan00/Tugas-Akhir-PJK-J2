# Tugas-Akhir-PJK-J2
# Percobaan Ping Antar Subnet (Router + Switch)

Percobaan ini bertujuan menguji konektivitas dua PC yang berada pada subnet berbeda, sebelum dan sesudah router dikonfigurasi.

---

### 1. Ping RTO (Gagal)
Sebelum router dikonfigurasi, PC-A melakukan ping ke PC-B:

Hasilnya **Request Timed Out**, karena tidak ada gateway yang meneruskan paket antar subnet.

**Bukti:**
![Ping RTO](rto.png)

---

### 2. Ping Sukses (Berhasil)
Setelah router dan switch dikonfigurasi dengan IP dan `no shutdown`, ping ulang:

Hasilnya **Reply**, menandakan paket berhasil diteruskan oleh router.

**Bukti:**
![Ping Success](success.png)

---

### Kesimpulan
- Tanpa router, perangkat beda subnet **tidak dapat saling ping**.
- Setelah konfigurasi router aktif, koneksi antar subnet **berhasil**.

Tautan Menuju video YouTube:
https://youtu.be/rnJCyyx6Jqc

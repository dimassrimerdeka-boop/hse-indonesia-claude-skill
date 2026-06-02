# Risk Matrix & HIRARC/IBPR — Panduan Penggunaan

Baca file ini ketika user meminta: risk assessment, HIRARC, IBPR, risk matrix,
penilaian risiko, atau prioritas pengendalian bahaya.

---

## Konsep Dasar

**Bahaya (Hazard):** Sumber, situasi, atau tindakan yang berpotensi
menyebabkan cedera/penyakit pada manusia, atau kerusakan properti/lingkungan.

**Risiko (Risk):** Kombinasi kemungkinan terjadinya kejadian berbahaya
dan keparahan dari cedera/kerugian yang dapat terjadi.

**HIRARC:** Hazard Identification, Risk Assessment, and Risk Control
**IBPR:** Identifikasi Bahaya dan Penilaian Risiko (padanan Indonesia)

---

## Risk Matrix 5x5

### Likelihood (Kemungkinan)

| Level | Nilai | Deskripsi |
|-------|-------|-----------|
| Almost Certain | 5 | Hampir pasti terjadi; > 1x per tahun di area |
| Likely | 4 | Sering terjadi; 1x per 1–5 tahun |
| Possible | 3 | Mungkin terjadi; 1x per 5–10 tahun |
| Unlikely | 2 | Jarang terjadi; 1x per 10–25 tahun |
| Rare | 1 | Sangat jarang; < 1x per 25 tahun |

### Severity (Keparahan)

| Level | Nilai | Dampak pada Manusia | Dampak Aset/Proses |
|-------|-------|--------------------|--------------------|
| Catastrophic | 5 | Fatality / kecacatan permanen massal | Kerusakan > 1 M, operasi berhenti total |
| Major | 4 | Kecacatan permanen / kehilangan fungsi | Kerusakan 500jt–1M, operasi terganggu signifikan |
| Moderate | 3 | Cedera serius / rawat inap | Kerusakan 100–500jt, gangguan operasi |
| Minor | 2 | Cedera ringan / rawat jalan | Kerusakan < 100jt, gangguan kecil |
| Insignificant | 1 | P3K saja / tidak ada cedera | Tidak ada kerusakan signifikan |

### Risk Score = Likelihood × Severity

### Risk Level & Tindakan

| Risk Score | Level | Warna | Tindakan |
|-----------|-------|-------|----------|
| 17–25 | EXTREME | Merah | Hentikan pekerjaan segera. Tidak boleh dilanjutkan tanpa pengendalian efektif. Eskalasi ke manajemen senior. |
| 10–16 | HIGH | Oranye | Prioritas tinggi. Terapkan pengendalian segera. Perlu persetujuan manajemen untuk melanjutkan. |
| 5–9 | MEDIUM | Kuning | Perlu pengendalian dalam waktu tertentu. Monitor rutin. |
| 1–4 | LOW | Hijau | Risiko dapat diterima. Pertahankan pengendalian yang ada. |

---

## Hierarki Pengendalian (Hierarchy of Controls)

Selalu terapkan pengendalian dari urutan tertinggi ke terendah:

```
1. ELIMINASI          — Hilangkan bahaya sepenuhnya (paling efektif)
2. SUBSTITUSI         — Ganti dengan yang lebih aman
3. REKAYASA TEKNIK    — Isolasi/modifikasi fisik (guard, ventilasi, dll)
4. ADMINISTRATIF      — Prosedur, pelatihan, rotasi, tanda peringatan
5. APD                — Alat Pelindung Diri (paling tidak efektif, last resort)
```

---

## Template HIRARC / IBPR

### Header Dokumen:
```
Judul       : HIRARC/IBPR [Area/Departemen]
Dokumen No  : [Nomor dokumen]
Tanggal     : [Tanggal penilaian]
Revisi      : [Nomor revisi]
Tim Penilai : [Nama-nama]
Disetujui   : [Nama & jabatan]
```

### Kolom Worksheet:

| No | Aktivitas | Bahaya | Potensi Risiko | L | S | Skor | Level | Pengendalian Existing | L' | S' | Skor' | Level' | Pengendalian Tambahan | PIC | Target |
|----|-----------|--------|---------------|---|---|------|-------|----------------------|----|----|----- -|--------|----------------------|-----|--------|

**Keterangan kolom:**
- **L** = Likelihood (sebelum pengendalian tambahan)
- **S** = Severity
- **Skor** = L × S
- **Pengendalian Existing** = Pengendalian yang sudah ada
- **L'** = Likelihood setelah pengendalian
- **S'** = Severity setelah pengendalian
- **Skor'** = Risiko residual
- **Level'** = Level risiko residual

---

## Contoh HIRARC — Aktivitas PDI Kendaraan

| No | Aktivitas | Bahaya | Potensi Risiko | L | S | Skor | Level | Pengendalian Existing | Pengendalian Tambahan |
|----|-----------|--------|---------------|---|---|------|-------|-----------------------|----------------------|
| 1 | Pengisian BBM kendaraan | Paparan uap bensin, percikan api | Kebakaran, keracunan | 3 | 5 | 15 | HIGH | Tidak merokok, APAR tersedia | Grounding equipment, APD: sarung tangan & masker organik |
| 2 | Pengoperasian car lift/hoist | Kegagalan mekanik, kendaraan jatuh | Fatality, kerusakan kendaraan | 2 | 5 | 10 | HIGH | Inspeksi rutin | Sertifikasi alat angkat, lock-out before work under vehicle |
| 3 | Pengecatan/finishing | Paparan uap cat (solvent) | Keracunan inhalasi, kebakaran | 3 | 3 | 9 | MEDIUM | Ventilasi, masker | Masker full-face dengan filter organic vapor, grounding |
| 4 | Pengisian refrigeran AC | Paparan refrigeran bertekanan | Luka bakar dingin, sesak napas | 2 | 3 | 6 | MEDIUM | Prosedur kerja | Pelatihan khusus, recovery machine, APD |
| 5 | Mendorong kendaraan | Tertabrak, terjepit | Cedera musculoskeletal | 3 | 2 | 6 | MEDIUM | Prosedur 2-orang | Komunikasi verbal, area kerja bebas hambatan |

---

## HIRARC untuk Pekerjaan Non-Rutin / High-Risk

Untuk pekerjaan berikut, **wajib** buat JSA terpisah + Permit to Work:

| Jenis Pekerjaan | Jenis Permit |
|-----------------|-------------|
| Hot work (las, gerinda, pemotongan) | Hot Work Permit |
| Pekerjaan di ketinggian > 1.8 m | Working at Height Permit |
| Confined space (ruang terbatas) | Confined Space Entry Permit |
| Pekerjaan listrik (tegangan > 50V AC) | Electrical Work Permit |
| Pekerjaan dengan excavation | Excavation Permit |
| Isolasi/lockout energi | LOTO Permit |

---

## Frekuensi Review HIRARC

| Kondisi | Frekuensi Review |
|---------|-----------------|
| Rutin (tanpa perubahan) | Minimal 1x per tahun |
| Ada insiden/near miss | Segera setelah insiden |
| Ada perubahan proses/peralatan | Sebelum perubahan diimplementasikan |
| Ada perubahan regulasi | Saat regulasi berlaku |
| Hasil audit menyatakan tidak efektif | Segera |

---

## Catatan Penggunaan

- Risk matrix ini adalah **contoh umum** — perusahaan dapat mengadaptasi
  definisi L & S sesuai konteks bisnis spesifik
- Beberapa industri memiliki risk matrix standar sendiri (migas: ALARP framework,
  konstruksi: sesuai SIS atau OHSAS)
- Semua HIRARC harus dikerjakan secara **partisipatif** — libatkan pekerja
  yang benar-benar melakukan pekerjaan tersebut
- Risiko residual yang masih HIGH/EXTREME setelah pengendalian = **tidak dapat
  diterima**, harus eskalasi ke manajemen

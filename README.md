# 🦺 HSE Indonesia — Claude Skill

> **First open-source HSE/K3 skill for Claude AI — built for Indonesian regulatory context**
>
> [![Claude Skill](https://img.shields.io/badge/Claude-Skill-orange?logo=anthropic)](https://claude.ai)
> [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
> [![Regulasi](https://img.shields.io/badge/Regulasi-PP%2050%2F2012%20%7C%20Kemnaker-blue)](https://jdih.kemnaker.go.id)
>
> ---
>
> ## 📋 Tentang Skill Ini
>
> **HSE Indonesia** adalah Claude Skill yang memberikan keahlian praktis K3 (Keselamatan & Kesehatan Kerja) dengan prioritas regulasi Indonesia — bukan sekadar terjemahan standar internasional.
>
> Dibuat oleh praktisi HSE aktif dengan sertifikasi **Ahli K3 Umum Kemnaker**, skill ini dirancang untuk langsung menghasilkan dokumen dan analisis yang siap pakai di lapangan.
>
> ### Apa yang bisa dilakukan?
>
> | Kategori | Kemampuan |
> |----------|-----------|
> | 📄 **Dokumen K3** | JSA, HIRARC/IBPR, SOP, Permit to Work, Safety Induction |
> | 🔍 **Audit & Compliance** | SMK3 gap analysis, CSMS scoring, ISO 45001 mapping |
> | 🏛️ **Organisasi K3** | P2K3 (Permenaker 13/2025), SK, notulen, laporan triwulan |
> | ⚠️ **Manajemen Risiko** | Risk matrix 5×5, CAPA tracking, bow-tie analysis |
> | 🧪 **B3 & Lingkungan** | Inventaris B3, manifest limbah, TPS compliance, SDS |
> | 📊 **Pelaporan** | Laporan insiden/kecelakaan, statistik K3 (FR, SR, TRIR) |
> | 🎓 **Training** | Materi safety induction, toolbox meeting, modul pelatihan |
>
> ---
>
> ## 🗂️ Struktur File
>
> ```
> hse-indonesia-claude-skill/
> ├── SKILL.md                          # File utama skill
> ├── smk3-12-elemen.md                 # 12 elemen PP 50/2012 + kriteria audit
> ├── p2k3-permenaker13-2025.md         # Panduan P2K3 terbaru
> ├── b3-compliance.md                  # Regulasi B3, limbah B3, GHS
> └── risk-matrix-guide.md              # HIRARC/IBPR & risk matrix 5×5
> ```
>
> ---
>
> ## ⚖️ Regulasi yang Dicakup
>
> - **UU No. 1/1970** — Keselamatan Kerja
> - - **PP No. 50/2012** — Penerapan SMK3
>   - - **PP No. 22/2021** — Perlindungan & Pengelolaan LH (B3)
>     - - **Permenaker No. 13/2025** — P2K3 (terbaru)
>       - - **Kepmenaker No. 187/1999** — Bahan Kimia Berbahaya
>         - - **ISO 45001:2018** — sebagai referensi pendukung
>          
>           - ---
>
> ## 🚀 Cara Install
>
> ### Di Claude.ai
> 1. Download file `SKILL.md` dari repo ini
> 2. 2. Buka [claude.ai](https://claude.ai) → Settings → Skills
>    3. 3. Upload `SKILL.md`
>       4. 4. Skill aktif dan siap digunakan
>         
>          5. ### Di Claude Code / Claude Desktop
>          6. ```bash
>             git clone https://github.com/dimassrimerdeka-boop/hse-indonesia-claude-skill.git
>             cp -r hse-indonesia-claude-skill ~/.claude/skills/hse-indonesia/
>             ```
>
> ---
>
> ## 💬 Contoh Penggunaan
>
> ```
> "Buatkan JSA untuk pekerjaan pengisian BBM kendaraan di area PDI"
> "Buat checklist audit SMK3 untuk elemen 6"
> "Draft SK Pembentukan P2K3 untuk perusahaan 150 karyawan"
> "Susun HIRARC untuk aktivitas pengoperasian car lift di workshop otomotif"
> "Buat laporan kecelakaan kerja format Kemnaker"
> ```
>
> ---
>
> ## ⚠️ Disclaimer
>
> Skill ini adalah alat bantu berbasis AI. Untuk implementasi formal, verifikasi selalu ke **Kemnaker/JDIH** dan konsultasikan dengan **Ahli K3 Umum bersertifikat**.
>
> ---
>
> ## 👤 Tentang Pembuat
>
> Dikembangkan oleh **Dimas Sri Merdeka** — Ahli K3 Umum (Kemnaker), 12+ tahun di industri otomotif & logistik.
>
> ---
>
> ## 🤝 Kontribusi
>
> Pull request dan issue sangat disambut! Khususnya untuk penambahan regulasi sektoral, template dokumen, atau koreksi regulasi terbaru.
>
> ---
>
> ## 📄 Lisensi
>
> MIT License — bebas digunakan dengan mencantumkan atribusi.
>
> ---
>
> <div align="center">
  <sub>⭐ Jika skill ini bermanfaat, berikan star di repo ini!</sub>
  </div>

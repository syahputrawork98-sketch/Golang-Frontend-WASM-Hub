# 🐹 Golang Frontend & WASM: The Hypermedia & Binary Engine

> **"Go is not just for the server; it's the high-performance engine for the modern web UI."**

Repositori ini adalah **Blueprint Utama (Rak 03)** dalam ekosistem *The Learning Matrix*. Fokus utamanya adalah mengeksplorasi pembangunan antarmuka pengguna menggunakan Golang melalui dua jalur: **Hypermedia (HTMX)** dan **WebAssembly (WASM)**.

---

## 🎯 Visi Arsitektural: Backend-Driven UI (The Why)
Golang Frontend Hub menantang dominasi JavaScript dengan menawarkan stabilitas tipe data dan performa biner di sisi klien:
1.  **HTMX (The Bridge)**: Menghidupkan kembali HATEOAS dengan membiarkan server Go mengirimkan fragmen HTML langsung ke DOM.
2.  **WebAssembly (The Power)**: Mengeksekusi biner Go di dalam browser untuk komputasi berat yang melampaui batas kecepatan JS.
3.  **Go Templates (The Source)**: Mesin render sisi server yang efisien dan aman.

Visi repositori ini adalah membedah **Golang as a UI Driver**:
1. **Server-Side Interactivity**: Bagaimana HTMX mengurangi kompleksitas state di frontend.
2. **Binary Performance**: Optimasi TinyGo dan WASM bindings untuk interaksi 120 FPS.
3. **Type-Safe UI**: Membawa disiplin tipe data Go ke dalam manipulasi elemen visual.

## 🧬 Jalur Matriks: Matrix Cross-Path (The What)
Sesuai konstitusi `00-Mapping-Road`, hub ini adalah persilangan:
- **Sumbu-Y**: Golang (Logic Core).
- **Sumbu-X**: RAK-02 (Native/Server Runtime) ➡️ **RAK-03 (Digital UI Hub)**.

Di sini kita belajar **"Bagaimana Golang melukis visualisasi tanpa ketergantungan NPM yang berat"**.

---

## 🏗️ Struktur 8-Rak (The Taxonomy)
1. **RAK-01: Anatomy & Landscape** (Evolusi Go UI, Template vs WASM).
2. **RAK-02: Foundation & Core Rules** (Go HTML Templates & Standard Library).
3. **RAK-03: Evolution & Interfacing** (HTMX deep-dive: Swapping, Triggers, & OOB).
4. **RAK-04: Core Mechanics & Internals** (WebAssembly Internals: memory, syscall/js).
5. **RAK-05: Ecosystem & Tooling** (TinyGo vs Standard Go for WASM, A-Frame/Ebitengine).
6. **RAK-06: The Underworld** (Shared Memory Buffer, FFI in Browser).
7. **RAK-07: Specialization** (Real-time Dashboards, High-performance Physics in Browser).
8. **RAK-08: Matrix Intersection** (The Bridge: How Go UI talks to Rust/TS Services).

---

## 📊 Status Proyek
Detail status per Rak dapat dilihat di [status.md](./status.md).

> [!NOTE]
> Proyek ini mengikuti standar dokumentasi **Gold Standard PPM V4**.

- `README.md` adalah pendahuluan ini.
- `docs/` berisi dokumentasi pendukung (pemetaan, aturan, referensi).
- `RAK-xx/` berisi semua rak utama.

## Dokumentasi
- [docs/root-governance.md](./docs/root-governance.md)
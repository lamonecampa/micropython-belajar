# MicroPython Belajar

Situs pembelajaran MicroPython berbahasa Indonesia, dari pemula hingga mahir. Situs statis tanpa build step dan dapat di-host melalui GitHub Pages.

## Fitur
- 30 artikel berurutan dalam lima tingkat kemahiran.
- Cakupan lintas platform: ESP32, ESP8266, RP2040/Pico, STM32, dan board Arduino tertentu yang kompatibel.
- Contoh kode, referensi dokumentasi resmi, dan catatan kompatibilitas.
- Desain responsif untuk desktop dan ponsel.

## Menjalankan secara lokal
```bash
python -m http.server 8000
``
Buka http://localhost:8000.

## Mengaktifkan GitHub Pages
1. Buka Settings → Pages pada repository.
2. Pilih Deploy from a branch.
3. Pilih branch `main` dan folder `/ (root)`.
4. Simpan. GitHub akan menerbitkan situs setelah deployment selesai.
5. URL biasanya `https://lamonecampa.github.io/micropython-belajar/`.

## Struktur
- `index.html`: beranda dan peta kurikulum.
- `artikel/`: 30 artikel.
- `assets/css/`: style utama dan artikel.
- `assets/images/diagrams/`: diagram edukatif SVG orisinal yang digunakan di artikel.
- `credits-gambar.md`: daftar aset visual, atribusi, dan referensi.
- `assets/js/`: interaksi UI.
- `tentang.html`: prinsip dan catatan kompatibilitas.

## Catatan teknis
MicroPython memiliki implementasi/port berbeda per keluarga chip. Nomor pin, API PWM/ADC, periferal, alamat flash, dan driver dapat berbeda antar board serta versi firmware. Ikuti dokumentasi resmi target perangkat. Proses flashing dan erase dapat menghapus isi flash perangkat.

## Referensi utama
- [MicroPython Documentation](https://docs.micropython.org/en/latest/)
- [MicroPython Downloads](https://micropython.org/download/)
- [Mischianti: Basic tools and firmware](https://mischianti.org/micropython-with-esp8266-and-esp32-flashing-firmware-and-programming-with-basic-tools-1/)
- [Mischianti: Thonny IDE](https://mischianti.org/micropython-with-esp8266-and-esp32-flashing-firmware-and-using-thonny-ide-2/)
- [Mischianti: PyCharm IDE](https://mischianti.org/micropython-with-esp8266-and-esp32-flashing-firmware-and-using-pycharm-ide-3/)
- [Mischianti: MicroPython Language](https://mischianti.org/category/micropython-language/)
- [Arduino MicroPython guide](https://docs.arduino.cc/micropython/first-steps/install-guide/)

Materi disusun ulang secara mandiri dalam bahasa Indonesia. Sumber bacaan eksternal ditautkan sebagai referensi dan bukan disalin utuh.

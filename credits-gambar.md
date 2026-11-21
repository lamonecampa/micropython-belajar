# Kredit dan Sumber Gambar

## Kebijakan penggunaan visual

Diagram yang tampil di 30 artikel dibuat khusus untuk situs **MicroPython Belajar** dalam format SVG. Diagram bukan hasil tangkapan layar, bukan salinan gambar dari situs lain, dan tidak menggunakan logo atau foto produk pihak ketiga. Karena itu, tidak ada gambar dari artikel Mischianti atau dokumentasi vendor yang diunduh dan diterbitkan ulang di repository ini.

**Atribusi standar untuk seluruh diagram:** Ilustrasi orisinal MicroPython Belajar, 2026. Lisensi: MIT (mengikuti lisensi repository).

## Daftar aset visual

| Berkas | Pokok bahasan | Digunakan untuk |
|---|---|---|
| `konsep-micropython.svg` | Alur kode, firmware, periferal, dan aksi perangkat | Artikel 01, 07 |
| `toolchain.svg` | IDE, koneksi serial, firmware, REPL | Artikel 02, 12, 18 |
| `ide-thonny.svg` | Alur umum editor, interpreter, koneksi perangkat, dan eksekusi | Artikel 05, 06 |
| `flash-firmware.svg` | Tahapan flashing firmware | Artikel 03 |
| `board-ecosystem.svg` | Keluarga board dan pemeriksaan dukungan firmware | Artikel 04 |
| `gpio-wiring.svg` | Konsep rangkaian GPIO, resistor, LED, dan ground | Artikel 09, 11 |
| `analog-pwm.svg` | Pembacaan ADC dan keluaran PWM | Artikel 10 |
| `peripheral-bus.svg` | Bus I²C, SPI, dan UART | Artikel 13, 14 |
| `iot-network.svg` | Perangkat, jaringan, broker/API, dan dashboard | Artikel 16, 19, 20, 24, 25, 27, 30 |
| `async-storage.svg` | Coroutine, timer, penyimpanan, pengujian, deployment | Artikel 08, 15, 17, 21, 22, 23, 26, 28, 29 |

## Referensi teknis untuk verifikasi

Diagram merupakan skema konseptual, bukan wiring diagram final atau pinout board tertentu. Verifikasi implementasi pada dokumentasi target perangkat:

- [MicroPython Documentation](https://docs.micropython.org/en/latest/)
- [MicroPython Downloads dan daftar board](https://micropython.org/download/)
- [MicroPython Quick Reference](https://docs.micropython.org/en/latest/quickref.html)
- [MicroPython machine module](https://docs.micropython.org/en/latest/library/machine.html)
- [MicroPython network module](https://docs.micropython.org/en/latest/library/network.html)
- [Thonny Documentation](https://thonny.org/)
- [PyCharm Documentation](https://www.jetbrains.com/help/pycharm/)
- [esptool Documentation](https://docs.espressif.com/projects/esptool/en/latest/)

## Catatan penting

- Atribusi sumber tidak otomatis memberikan izin untuk menyalin gambar pihak lain. Untuk alasan itu, visual eksternal hanya ditautkan sebagai referensi, bukan disalin ke repository.
- Dukungan MicroPython berbeda antarboard dan antarport. Jangan menganggap seluruh board Arduino kompatibel; periksa daftar port/firmware yang tersedia.
- Diagram GPIO tidak menentukan nomor pin atau tegangan. Periksa datasheet board, batas arus, dan level logika sebelum merangkai perangkat.

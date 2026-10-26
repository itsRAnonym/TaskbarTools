# NetSpeedTaskbar

Kecepatan download dan upload langsung di taskbar Windows 10, sebagai **toolbar asli** (klik kanan taskbar > Toolbars).
Ikut kunci/buka kunci taskbar, bisa digeser, tidak menutupi aplikasi, dan ringan. Satuan (MB/s, KB/s, Mbps, Kbps, otomatis)
dan jumlah desimal bisa diatur.

## Unduh

Ambil zip terbaru di halaman [Releases](https://github.com/GANTI-USERNAME/TaskbarTools/releases)
(yang berawalan `NetSpeedTaskbar-`). Cocokkan hash-nya dengan file `.sha256` di halaman yang sama:

```
certutil -hashfile NetSpeedTaskbar-X.Y.Z-win-x64.zip SHA256
```

## Pasang

Syarat: Windows 10 (64-bit) dan [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) (x64).

1. Ekstrak zip ke folder **permanen**, mis. `C:\Program Files\NetSpeedTaskbar`.
2. Jalankan `NetSpeedTaskbar.exe` sekali.
3. Klik kanan `install.bat` > **Run as administrator**. Explorer akan restart sebentar.
4. Klik kanan taskbar > **Toolbars** > **NetSpeedTaskbar**.

Menggeser posisi: buka kunci taskbar. Pengaturan satuan dan desimal: klik kanan kotaknya.
Detail lengkap ada di `BACA-SAYA.txt` di dalam zip.

## Privasi dan keamanan

- Tidak ada telemetri. Cek update (opsional, bisa dimatikan) hanya menanyakan nomor versi terbaru ke GitHub.
- Komponen `NetSpeedBand.dll` dimuat di dalam `explorer.exe`. Kalau taskbar bermasalah, jalankan `uninstall.bat` sebagai Administrator.
- Aplikasi belum ditandatangani (code signing), jadi SmartScreen bisa memberi peringatan. Cocokkan hash sebelum menjalankan.

## Lapor masalah

Buka [Issues](https://github.com/GANTI-USERNAME/TaskbarTools/issues/new/choose). Sebutkan versi Windows dan ukuran ikon taskbar (besar/kecil).

## Lisensi

Freeware, kode sumber tidak dibuka. Lihat [LICENSE.txt](LICENSE.txt).

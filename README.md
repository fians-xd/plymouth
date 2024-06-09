# Mengubah Tema Plymouth

Panduan ini akan memandu Anda melalui langkah-langkah untuk mengubah tema Plymouth di sistem Ubuntu Anda. Plymouth adalah aplikasi yang menampilkan splash screen grafis saat booting dan mematikan sistem.

<p align="center">
  <img src="preview/preview.gif" alt="Tema Plymouth Preview" width="200" height="200">
</p>

## Persiapan

1. **Update sistem Anda:**
    ```bash
    sudo apt update
    ```

2. **Instal Plymouth:**
    ```bash
    sudo apt install plymouth
    ```

## Mengubah Tema Plymouth

### Langkah 1: Pindahkan Tema ke Direktori Plymouth

Pindahkan tema Plymouth yang telah Anda siapkan ke direktori tema Plymouth:
```bash
sudo cp -r /path/to/your/theme /usr/share/plymouth/themes/temamu

# Mengubah Tema Boot Linux

Silahkan dicoba Bambang caranya dibawah 😉👇

<p align="center">
  <img src="preview/preview.gif" alt="Tema Plymouth Preview" width="180" height="200">
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

Pindahkan tema Plymouth yang sudah di siapkan ke direktori tema Plymouth:
```bash
sudo cp -r /path/to/your/theme /usr/share/plymouth/themes/temamu
```

### Langkah 2: Tambahkan tema yang baru ke daftar:
```bash
sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/your-theme-name/nama-temamu.plymouth 100
```

### Langkah 3: Pilih tema yang baru ditambahkan:
```bash
sudo update-alternatives --config default.plymouth
```

### Langkah 4: Restart sistem untuk melihat hasilnya:
```bash
sudo reboot
```

## Note:
# Silahkan bertanya jika ada kendala 👉 t.me/yansxdi

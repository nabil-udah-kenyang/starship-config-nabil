# ⭐ Starship Prompt Config — by Nabil

Konfigurasi Starship prompt milik Nabil.  
Ringan, cepat, dan membuat terminal kamu tampil jauh lebih rapi & informatif.

---

## 🚀 Apa Itu Starship?

Starship adalah prompt shell minimalis, sangat cepat, dan bisa dikustomisasi sepenuhnya.  
Digunakan di banyak shell: **Bash, Zsh, Fish, PowerShell, Nushell, dan lainnya**.

Website resmi: https://starship.rs  

---

# 📦 1. Install Starship (Wajib Sebelum Menggunakan Config Ini)

Jika pengguna **belum** menginstall Starship, cukup copy & paste perintah berikut:

---

## 🐧 Linux / macOS

```bash
curl -sS https://starship.rs/install.sh | sh
```

Tambahkan ke shell kamu:

### Bash
```bash
echo 'eval "$(starship init bash)"' >> ~/.bashrc
```

### Zsh
```bash
echo 'eval "$(starship init zsh)"' >> ~/.zshrc
```

### Fish
```bash
echo 'starship init fish | source' >> ~/.config/fish/config.fish
```

---

## 🪟 Windows (PowerShell)

Install Starship:

```powershell
winget install Starship.Starship
```

Aktifkan di PowerShell:

```powershell
Add-Content $PROFILE 'Invoke-Expression (&starship init powershell)'
```

---

# 📁 2. Install Config Ini

## 🔽 Clone config ke folder konfigurasi Starship

### Linux / macOS / WSL

```bash
git clone https://github.com/nabil-udah-kenyang/starship-config-nabil.git ~/.config/starship-config
```

Copy / symlink config:

```bash
ln -sf ~/.config/starship-config/starship.toml ~/.config/starship.toml
```

---

### Windows (PowerShell)

```powershell
git clone https://github.com/nabil-udah-kenyang/starship-config-nabil.git "$env:USERPROFILE\.config\starship-config"
Copy-Item "$env:USERPROFILE\.config\starship-config\starship.toml" "$env:USERPROFILE\.config\starship.toml" -Force
```

---

# ⚡ 3. Instalasi Cepat (One-liner)

Untuk Linux / macOS:

```bash
git clone https://github.com/nabil-udah-kenyang/starship-config-nabil.git ~/.config/starship-config \
&& ln -sf ~/.config/starship-config/starship.toml ~/.config/starship.toml
```

---

# 📄 4. Isi File Konfigurasi

Konfigurasi utama berada di:

```
starship.toml
```

Jika ingin modifikasi sesuai kebutuhan, gunakan dokumentasi resmi:

https://starship.rs/config  

---

# 📝 Lisensi

Bebas dipakai, modifikasi, dan dibagikan.


🚀 Windows RDP di Cloud via GitHub Actions

aiiiiii, selamat datang di AiraaCheisyaa CRD! 🎉
Di sini kamu bisa dapetin Remote Desktop (RDP) Windows Server 2022 langsung dari browser — powered by GitHub Actions.

👉 Gak perlu ribet instalasi, gak perlu keluar duit buat sewa VPS/RDP.
Cukup jalanin workflow, tunggu bentar, dan kamu udah bisa pakai Windows bersih dengan Google Chrome & Visual Studio Code yang udah siap pakai.

Cocok buat: coding, browsing, testing, atau sekadar ngerjain tugas yang butuh OS Windows.


---

✨ Fitur Keren

🖥️ Full Windows Server 2022 – pengalaman desktop Windows asli, langsung di cloud.

⚡ Setup Cepat – tinggal copy satu command → run workflow → boom! siap pakai kurang dari 5 menit.

⏱️ Durasi Panjang – sesi aktif sampai limit GitHub Actions (~6 jam).

🛠️ Pre-installed Software – Chrome + VS Code udah ready.

🔐 Aman & Private – tiap sesi jalan di runner terisolasi & otomatis dihapus setelah selesai.

💸 Gratis 100% – manfaatin kuota free dari GitHub Actions.



---

🔧 Cara Kerja di Balik Layar

Skrip ini bakal otomatis ngerjain semua:

1. 🚀 Bikin Runner → minta VM Windows Server 2022 dari GitHub.


2. 👤 Tambah User Admin → bikin akun Windows khusus buat kamu.


3. 📦 Install Otomatis → Chrome, VS Code, dan Chrome Remote Desktop (CRD).


4. 🧠 Konfigurasi CRD → ambil auth code dari command yang kamu kasih & setup host.


5. ⏱️ Keep Alive → sesi tetap jalan sampai ~6 jam.




---

📋 Panduan Penggunaan

Ikuti langkah simpel ini buat mulai pakai RDP:

🔹 Langkah 1: Fork Repo Ini

Klik tombol Fork di pojok kanan atas biar repo ini pindah ke akun GitHub kamu.

🔹 Langkah 2: Ambil Command CRD Headless

1. Buka Chrome Remote Desktop Setup.


2. Login pakai akun Google.


3. Klik Begin → Next → Authorize.


4. Pilih opsi command untuk Windows (Command Prompt / PowerShell).


5. Copy SELURUH command-nya.



🔹 Langkah 3: Run Workflow

1. Balik ke repo fork kamu → buka tab Actions.


2. Pilih workflow AiraaCheisyaa CRD.


3. Klik Run workflow.


4. Paste command dari langkah 2 ke input field → klik tombol hijau Run workflow.



🔹 Langkah 4: Connect ke RDP

1. Tunggu 2–3 menit sampai job jalan.


2. Buka log → cari bagian CREDENTIALS (isi user, password, & PIN).


3. Buka lagi halaman Chrome Remote Desktop → pilih host baru (misal gh-runner-123456).


4. Masukkan PIN default 123456, lalu login pakai user & password dari log.



🎉 Done! Sekarang kamu udah punya Windows RDP full di cloud.


---

⚠️ Cara Stop Sesi

Sesi otomatis jalan ~6 jam.
Kalau mau berhenti lebih cepat → buka Actions → cancel workflow yang lagi jalan.


---

📜 Lisensi

Project ini pakai MIT License.
Detail lengkap ada di file LICENSE.

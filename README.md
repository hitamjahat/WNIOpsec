# 🔒 Panduan Privasi Internet (Level Pemula sampai Expert)  

*Buat yang mau aman di internet, dari settingan dasar sampai mode ninja!*

---

## **Level 1: Gampang** 🌱  

*(Buat pemula, tinggal klik-klik doang)*  
**Yang Harus Dilakukan:**  

1. **Password Kuat** 💪: Jangan pake "123456" atau "password" 😑! Mix huruf besar-kecil, angka, simbol (contoh: `R4h4$!aM4n#`).  
2. **Verifikasi 2 Langkah* (2FA)* 🔐: Aktifin di semua akun penting. JANGAN GUNAKAN 2FA lewat SMS, Gunakan Aplikasi kayak KeeepassXC (PC, MacOS, Linux) KeepassDX (Android) dan Passwords (Bawaan iOS).  
3. **Privasi Medsos** 👤: Ganti settingan jadi "Private", matiin *tracking* iklan, jangan share alamat/nomor HP.  
4. **HTTPS Everywhere** 🔒: Pake browser yang ada gembok ijo (Chrome/Firefox), atau install ekstensi [HTTPS Everywhere](https://www.eff.org/https-everywhere).  
5. **Update Terus** 🔄: Nyalain auto-update biar ga kena hack bocoran celah lama.  

**Mindset** 🧠:  

- Jangan asal bagi info pribadi (e.g., "gue lahir di RS A tanggal XX/YY" bisa dipake buat bobol akun!).  
- Ingat: Kalau gratisan, lo yang jadi produk (data lo dijual!).  

---

## **Level 2: Lumayan** 🔍  

*(Buat yang udah sadar privasi, mau effort dikit)*  
**Yang Harus Dilakukan:**  

1. **Password Manager** 🗝️: Pake [Bitwarden](https://bitwarden.com/) atau [KeePass](https://keepass.info/) biar ga perlu hapal 100 password. Kalau saya lebih preefer menggunakan KeeepassXC (PC, MacOS, Linux) KeepassDX (Android) karena bisa file databasenya bisa dibuka di KeepassXC maupun KeepassDX, dan bisa disalin di flashdisk jaga jaga kalau filenya hilang. KeepassXC sendiri bisa untuk simpan password, generate password (sesuaikan dengan maksimum panjang password misal google maksimal 100 character ya generate aja 100 character), dan juga untuk simpan OTP/2FA. penggunaanya ada disini <https://www.youtube.com/watch?v=UaddgCned54> Jangan gunakan password yang sama, gunakan password yang berbeda beda di setiap layanan. Simpan password di keepassXC, untuk kenyamanan, database keepassXC bisa di copy ke hp and roid dan dibuka melalui aplikasi KeepassDX atau bisa copy paste ke aplikasi passwords bawaan iOS.
    1. Buka KeepasXC dan buat database seperti gambar dibawah ini
    ![alt text](https://github.com/hitamjahat/WNIOpsec/blob/main/1.png?raw=true)
    ![alt text](https://github.com/hitamjahat/WNIOpsec/blob/main/2.png?raw=true)
    ![alt text](https://github.com/hitamjahat/WNIOpsec/blob/main/3.png?raw=true)
    ![alt text](https://github.com/hitamjahat/WNIOpsec/blob/main/4.png?raw=true)
    2. Generate Password, maksimalkan, kalau yang dibolehin 100 ya mentokin aja 100, kalau ada beberapa character yang tidak boleh dipakai ya bisa klik tab exclude
    ![alt text](https://github.com/hitamjahat/WNIOpsec/blob/main/5.png?raw=true)
    3. Untuk password bawaan iOS sudah ada fitur autofill password dan username menggunakan Face ID Aktifkan 2FA di setiap layanan, gambar diatas adalah contoh pengaktifan 2FA di google, klik saja tombol authenticator, lalu klik setup authenticator, lalu klik cant scan it, copy secret key, buka keepassXC, klik kanan di gambar kunci kuning dari password dan username yang tadi sudah kita buat, pindahkan mouse ke TOTP, dan akan muncul setup TOTP, klik dan masukan secret key dari google tadi, klik default setting, dan klik ok. Nanti kalau mau pakai 2FA tinggal klik kanan, TOTP, show TOTP maka kode akan keluar, ini berlaku di PC, linux, MacOS, dan android.
    https://github.com/hitamjahat/WNIOpsec/blob/main/6.png
    https://github.com/hitamjahat/WNIOpsec/blob/main/7.png
    https://github.com/hitamjahat/WNIOpsec/blob/main/8.png
    4. Untuk pengguna iOS bisa buka aplikasi passwords, klik passwords, buka saved passwords, klik edit, lalu klik set up code, Scan QR code with camera, lalu buka keepassxc di pc laptop, klik kanan, TOTP lalu show QR Code, scan QR code, maka kode 2FA akan otomatis masuk ke aplikasi passwords, kode yang keluar akan sama dengan kode di keepassxc. JANGAN GUNAKAN NOMOR HP untuk otentikasi 2FA karena mudah diretas. Referensi untuk lebih lengkap: <https://www.youtube.com/watch?v=VEfkt29moE8>

2. **VPN Murah Meriah** 🛡️: Pilih VPN yang *no-log* kayak [Mullvad](https://mullvad.net/) buat sembunyiin IP lo.  
3. **Browser Anti Spy** 🕵️‍♀️: Ganti ke [Firefox](https://www.mozilla.org/) + ekstensi [uBlock Origin](https://ublockorigin.com/) (buat blok iklan *tracker*). Saya sarankan librewolf atau mullvadbrowser.
4. **Chat Aman** 💬: Pakai [Signal](https://signal.org/) atau WhatsApp (tapi harus aktifin *end-to-end encryption* di settings!). Telegram agak ngeri ngeri sedep tapi boleh dicoba.
5. **Waspada Phishing** 🎣: Jangan asal klik link email/text aneh! Cek alamat website sebelum login. Jangan tergiur link bokep aneh, jangan sering sering nonton bokep juga.

**Mindset** 🧠:  

- Anggap Wi-Fi publik itu sarang hacker (selalu pake VPN!).  
- Rutin cek izin aplikasi (matiin akses kamera/lokasi yang ga perlu). Kalau perlu matiin GPS, idupin kalo pas pake maps atau order gojek/grab (irit batre sama privacy terjaga)

---

## **Level 3: WNI** 🦸‍♂️  

*(Buat tech-geek yang ga takut ribet)*  
**Yang Harus Dilakukan:**  

1. **Ganti OS** 💻: Tinggalin Windows, coba [Linux] Debian/Arch/OpenBSD atau macOS. Kalo mau ekstra, pakai [Qubes OS](https://www.qubes-os.org/). Refrensi qubes os <https://www.youtube.com/watch?v=uRBgQAwRagQ>
2. **Mode Incognito Pro** 🕶️: Pake [Tor Browser](https://www.torproject.org/) buat browsing super rahasia.  
3. **Email Enkripsi** ✉️: Migrasi dari Gmail ke [Tutanota](https://tutanota.com/). Proton kemarin agak ngeri ngeri sedap, googling aja provider email yang aman.
4. **Enkripsi File** 📁: Rahasiain data pake [VeraCrypt](https://www.veracrypt.fr/) atau [Cryptomator](https://cryptomator.org/). File file yang bersifat penting dan membahayakan jiwa raga seperti scan KTP, KK, SIM, screenshoot cendol kasus wajit di enkripsi.  
5. **Jaringan Super Aman** 🌐: Pakai [Pi-hole](https://pi-hole.net/) buat blok iklan di router, sama randomisasi MAC address.  

**Mindset** 🧠:  

- Jangan serahin data ke cloud (mending self-host pake [Nextcloud](https://nextcloud.com/)). Serahkan diri hanya dengan yang Maha Kuasa.
- Prioritaskan software/apliaksi *open-source* ketimbang yang berbayar/tertutup.  

---

## **Level 4: WNI** 🥷  

*(lahir jadi WNI berat gan, udah harus survival mode, ibarat kata level langsung expert baru main 5 menit udah ketemu final boss)*  
**Yang Harus Dilakukan:**  

1. **Jaringan Kegelapan** 🌑: Kombinasi Tor + *bridges*, atau [I2P](https://geti2p.net/). Jangan lupa pakai [Tails OS](https://tails.net/) biar ga ninggalin jejak. Panduanya ada di <https://www.youtube.com/watch?v=u5Lv_HXICpo>
2. **Hardware Khusus** 🔑: Kunci akun pake [YubiKey](https://www.yubico.com/), simpan data penting kayak database KeepasXC dan lain lain di laptop *air-gapped* (ga pernah konek internet)/hardisk yang gak kecolok apapun, bisa dibuat kalung kaya Igor Saykoji.  
3. **Pisahkan Identitas** 👤: Bikin persona berbeda buat tiap aktivitas (e.g., akun medsos, kerja, dll.) + pake *virtual machine*. Bikin Email minimal 3/4. 1 buat personal/private use, yang menyangkut data data pribadi only, dipake buat apapun yang mengharuskan menggunakan data pribadi kaya Ebanking, djponline, daftar BPJS, kerjaan yang sifatnya buat nerima duit dll. Jangan share email tersebut, kalau bocor ya berarti providernya asshole. 1 lagi buat sosmed dan ecommerce, misal akun sosmedmu kena hack, data pribadimu aman karena beda email. 1 email burner, buat login login situs situs aneh, biasa kan mau pake service gratisan minta login email, nah ini waktunya email burner tampil, buat login situs situs kaya kaskus, figma, canva, chatgpt, behance, forum forum gajelas buat minta gratisan, bikin akun alter di twitter, ibarat kata emailmu yang ini bocor, data pribadi dan sosmed aman.
4. **Anti Mata-Mata Total** 🕵️:  
    - Ponsel *burner* + SIM anonim.  
    - Bayar pake Monero atau cash fisik. jangan pake qris, dikira nantang gelud.
    - Tas Faraday buat sembunyiin sinyal gadget. (paranoid level dewa)

**Mindset** 🧠:  

- Anggap semua aktivitas online lo diawasi (meski ga ada bukti).  
- Cek metadata (e.g., EXIF foto, log DNS) tiap hari!, untuk whistle blower hapus semua metadata sebelum upload file, cek di <https://github.com/sh1d0wg1m3r/Metadata-Removal-Tool>

---

### **Kategori Tambahan** 🧰  

Berikut beberapa kategori spesifik buat kebutuhan privasi lo:  

#### **Instant Messaging** 💬  

- **Gampang**: WhatsApp (aktifin E2EE), Telegram (mode Secret Chat).  
- **Lumayan**: [Signal](https://signal.org/) (enkripsi end-to-end, open-source).  
- **WNI**: [Matrix](https://matrix.org/) + [Element](https://element.io/) (self-host, super aman).  

#### **Encrypted DNS** 🌐  

- **Gampang**: Pake [Cloudflare DNS](https://1.1.1.1/) atau [Google DNS](https://dns.google/).  
- **Lumayan**: [NextDNS](https://nextdns.io/) (bisa custom blocklist).  
- **WNI**: [DNSCrypt](https://dnscrypt.info/) atau self-host DNS pake [Pi-hole](https://pi-hole.net/).  

#### **File Encryption** 🔐  

- **Gampang**: Zip file pake password.  
- **Lumayan**: [VeraCrypt](https://www.veracrypt.fr/) (enkripsi partisi/disk).  
- **WNI**: [Cryptomator](https://cryptomator.org/) (enkripsi file sebelum upload ke cloud).  

#### **File Sharing & Sync** 📂  

- **Gampang**: Google Drive/Dropbox (tapi hati-hati sama privasi).  
- **Lumayan**: [Nextcloud](https://nextcloud.com/) (self-host, lebih aman).  
- **WNI**: [Syncthing](https://syncthing.net/) (file sync tanpa cloud, peer-to-peer).  

#### **Disk Cleaners** 🧹  

- **Gampang**: CCleaner (buat bersihin file sampah).  
- **Lumayan**: [BleachBit](https://www.bleachbit.org/) (open-source, lebih dalam).  
- **WNI**: [ShredOS](https://github.com/PartialVolume/shredos.x86_64) (nge-wipe disk biar ga bisa dipulihin).  

#### **Dead Man's Switch** ⏰  

- **Lumayan**: [Dead Man's Switch](https://www.deadmansswitch.net/) (kirim email otomatis kalo lo ga aktif).  
- **WNI**: Buat script sendiri pake Python atau tools kayak [IFTTT](https://ifttt.com/).  

#### **Photo Storage** 📸  

- **Gampang**: Google Photos (tapi privasi kurang).  
- **Lumayan**: [Cryptee](https://crypt.ee/) (enkripsi foto sebelum upload).  
- **WNI**: Self-host pake [Nextcloud](https://nextcloud.com/) atau [PhotoPrism](https://photoprism.app/).  

#### **Web Search** 🔍  

- **Gampang**: Google (tapi data lo dilacak).  
- **Lumayan**: [DuckDuckGo](https://duckduckgo.com/) (no tracking).  
- **WNI**: [Searx](https://searx.me/) (self-host, gabungin hasil search dari banyak mesin).  

#### **Encrypted Notebooks** 📝  

- **Gampang**: Google Keep (tapi kurang aman).  
- **Lumayan**: [Standard Notes](https://standardnotes.com/) (enkripsi end-to-end).  
- **WNI**: [Joplin](https://joplinapp.org/) + enkripsi pake VeraCrypt.  

#### **Encrypted Calendar** 📅  

- **Gampang**: Google Calendar (tapi privasi kurang).  
- **Lumayan**: [Proton Calendar](https://proton.me/calendar) (enkripsi end-to-end).  
- **WNI**: Self-host pake [Nextcloud Calendar](https://nextcloud.com/).  

#### **Productivity & Work** 💼  

- **Gampang**: Google Workspace/Microsoft 365 (tapi data lo dilacak).  
- **Lumayan**: [OnlyOffice](https://www.onlyoffice.com/) atau [LibreOffice](https://www.libreoffice.org/) (offline, open-source).  
- **WNI**: Self-host pake [Nextcloud](https://nextcloud.com/) + [Collabora Online](https://www.collaboraoffice.com/).  

#### **Whistleblower Tools** 📢  

- **Lumayan**: [SecureDrop](https://securedrop.org/) (buat kirim dokumen rahasia ke media).  
- **WNI**: [GlobaLeaks](https://www.globaleaks.org/) (self-host, buat whistleblower).  

#### **Android Alternative OS** 📱  

- **Lumayan**: [LineageOS](https://lineageos.org/) (Android tanpa bloatware). Pastikan menggunakan MicroG
- **WNI**: [GrapheneOS](https://grapheneos.org/) (fokus privasi & keamanan).  

---

### **Catatan Penting** ⚠️  

- **Sesuaikan Level**: Ga perlu level expert kalo cuma mau amankan akun medsos.  
- **Nggak Nyaman Tapi Aman**: Makin aman = makin ribet (e.g., internet lewat Tor itu lelet!).  
- **Update Ilmu**: Ikuti komunitas kayak [Privacy Guides](https://www.privacyguides.org/) atau [EFF](https://www.eff.org/).  

**Terakhir** 🏁: Privasi itu kayak olahraga—mulai pelan-pelan, tapi konsisten! untuk whistle blower/Aktivis atau apapun kegiatanya yang bisa mengancam kehidupunk bisa baca baca <https://web.archive.org/web/20240529094033/https://anonymousplanet.org/export/guide.pdf>, <https://media.defcon.org/DEF%20CON%2030/DEF%20CON%2030%20presentations/Sam%20Bent%20-%20Tor%20Darknet%20Opsec%20By%20a%20Veteran%20Darknet%20Vendor.pdf>, <https://www.privacytools.io/> sehat selalu dan viva la resistance🔒  

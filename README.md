# 🌊 KhazarOS GNU/Linux 0.0.1 (Khazar)

Select your preferred language / İstediğiniz dili seçin / İstədiyiniz dili seçin:

* [🇬🇧 English Version](#-english-version)
* [🇹🇷 Türkçe Versiyon](#-türkçe-versiyon)
* [🇦🇿 Azərbaycan Versiyası](#-azərbaycan-versiyası)

---

## 🇬🇧 English Version
download link:https://drive.google.com/file/d/154bj5KqICu6cSH3H6OJEWKC7mNZivv6P/view?usp=sharing
KhazarOS is a custom GNU/Linux distribution built on top of the stable Kubuntu (Ubuntu/Debian) base, fully optimized for the Azerbaijani language and national visual identity. The system is designed for daily users, developers, and cybersecurity enthusiasts who prefer terminal-centric environments.

### 🎯 Project Philosophy & Features
* **National Visual Identity:** From the system boot (GRUB, Plymouth) to the login screen (SDDM), installer (Calamares), and desktop, the environment is fully customized with KhazarOS branding and Baku-themed wallpapers.
* **Native Language & Keyboard Support:** Azerbaijani (az_AZ) is configured as the default system language, and the Azerbaijani QWERTY keyboard layout comes pre-configured out of the box.
* **Minimalist & Powerful (No-Market):** In alignment with the philosophy of professional systems like Kali Linux and Arch Linux, the graphical software store (`plasma-discover`) has been completely removed. Software management is handled directly via the terminal (`apt`, `git`, `pip`).
* **Update Protection:** Core packages that define the visual and kernel identity of the system are locked (`apt-mark hold`). This ensures that when the user upgrades the system (`apt upgrade`), KhazarOS branding and themes are never overwritten.

### 🗜️ ISO Compression and Packaging Settings
To balance build speed and file size, the following configuration was applied during the Cubic ISO compression phase:
* **Selected Algorithm:** `gzip` (or `lz4`)
* **Reason:** Avoids the ultra-slow build times and high CPU strain associated with `xz`. `gzip` compresses the initial 5 GB base down to roughly 3 GB, delivering fast packaging and an optimized file size.

### 🚀 Future Plans (KhazarOS 2.0 Roadmap)
- [ ] Setting up a dedicated KhazarOS software repository server.
- [ ] Direct integration of Azerbaijani national digital signatures (e-imza) and ASAN Imza.
- [ ] Pre-installing popular OSINT and network analysis tools for security researchers.

[Back to Top ↑](#-khazaros-gnulinux-10-khazar)

---

## 🇹🇷 Türkçe Versiyon
indirme linki:https://drive.google.com/file/d/154bj5KqICu6cSH3H6OJEWKC7mNZivv6P/view?usp=sharing
KhazarOS, kararlı Kubuntu (Ubuntu/Debian) tabanı üzerine inşa edilmiş, tamamen Azerbaycan diline ve milli görsel kimliğe göre optimize edilmiş özel bir GNU/Linux dağıtımıdır. Sistem, hem günlük kullanıcılar hem de terminal odaklı çalışmayı seven programcılar ve siber güvenlik meraklıları için optimize edilmiştir.

### 🎯 Proje Felsefesi ve Özellikleri
* **Milli Görsel Kimlik:** Sistem açılışından (GRUB, Plymouth) itibaren giriş ekranı (SDDM), yükleyici (Calamares) ve masaüstü, tamamen KhazarOS logoları ve Bakü manzaralı duvar kağıtları ile özelleştirilmiştir.
* **Yerel Dil ve Klavye Desteği:** Azerbaycan dili (az_AZ) varsayılan sistem dili olarak ayarlanmış ve Azerbaycan QWERTY klavye düzeni standart olarak entegre edilmiştir.
* **Minimalist ve Güçlü (Market Yok):** Kali Linux ve Arch Linux gibi profesyonel sistemlerin mantığına uygun olarak, sistemle birlikte gelen grafiksel uygulama mağazası (`plasma-discover`) tamamen kaldırılmıştır. Yazılım yönetimi doğrudan terminal üzerinden (`apt`, `git`, `pip`) gerçekleştirilir.
* **Güncelleme Koruması:** Sistemin görsel ve kimlik yapısını oluşturan ana paketler kilitlenmiştir (`apt-mark hold`). Bu sayede kullanıcı sistemi güncellediğinde (`apt upgrade`) KhazarOS isimleri ve temaları asla silme işlemiyle karşılaşmaz.

### 🗜️ ISO Sıkıştırma ve Paketleme Ayarları
Sistemin derlenme hızı ve dosya boyutu dengesini korumak için Cubic ISO sıkıştırma aşamasında aşağıdaki konfigürasyon uygulanmıştır:
* **Seçilen Algoritma Mantığı:** `gzip` (veya `lz4`)
* **Nedeni:** `xz` algoritmasının ultra yavaş çalışmasını ve işlemciyi saatlerce %100 yükte tutmasını engellemek. `gzip`, 5 GB'lık ham tabanı yaklaşık 3 GB civarına indirerek hem hızlı paketleme hem de optimal dosya boyutu sağlar.

### 🚀 Gelecek Planları (KhazarOS 2.0 Yol Haritası)
- [ ] Özel KhazarOS Yazılım Deposu (Repo Sunucusu) kurulması.
- [ ] Azerbaycan'ın yerel dijital imza (e-imza) ve ASAN İmza sistemlerinin entegrasyonu.
- [ ] Siber güvenlik araştırmacıları için popüler OSINT ve ağ analiz araçlarının hazır kurulu gelmesi.

[Back to Top ↑](#-khazaros-gnulinux-10-khazar)

---

## 🇦🇿 Azərbaycan Versiyası
yükləmək üçün link:https://drive.google.com/file/d/154bj5KqICu6cSH3H6OJEWKC7mNZivv6P/view?usp=sharing
KhazarOS — sabit Kubuntu (Ubuntu/Debian) bazası üzərində qurulmuş, tamamilə Azərbaycan dilinə və milli vizual kimliyə uyğunlaşdırılmış xüsusi GNU/Linux distributividir. Sistem həm gündəlik istifadəçilər, həm də terminal mərkəzli mühitləri sevən proqramçılar və kibertəhlükəsizlik həvəskarları üçün optimallaşdırılmışdır.

### 🎯 Layihənin Fəlsəfəsi və Özəllikləri
* **Milli Vizual Kimlik:** Sistemin açılışından (GRUB, Plymouth) başlayaraq giriş ekranı (SDDM), quraşdırıcı (Calamares) və iş masası tamamilə KhazarOS loqoları və Bakı mənzərəli divar kağızları ile fərdiləşdirilmişdir.
* **Doğma Dil və Klavye Dəstəyi:** Azərbaycan dili (az_AZ) standart sistem dili olaraq təyin edilmiş və Azərbaycan QWERTY klaviatura düzümü hazır tənzimlənmiş olaraq gəlir.
* **Minimalist və Güclü (Mağazasız):** Kali Linux və Arch Linux gibi peşəkar sistemlərin məntiqinə uyğun olaraq, sistemlə gələn qrafik proqram mağazası (`plasma-discover`) tamamilə silinmişdir. Proqram təminatının idarə edilməsi birbaşa terminal vasitəsilə (`apt`, `git`, `pip`) həyata keçirilir.
* **Yenilənmə Qoruması:** Sistemin vizual və nüvə kimliyini formalaşdıran əsas paketlər dondurulmuşdur (`apt-mark hold`). Bu sayədi istifadəçi sistemi yenilədikdə (`apt upgrade`) KhazarOS adları və mövzuları əsla silinmir və ya dəyişdirilmir.

### 🗜️ ISO Sıxılma və Paketləmə Ayarları
Sistemin yığılma sürəti və fayl ölçüsü balansını qorumaq üçün Cubic ISO sıxılma mərhələsində aşağıdakı konfigürasiya tətbiq edilmişdir:
* **Seçilmiş Alqoritm:** `gzip` (və ya `lz4`)
* **Səbəbi:** `xz` alqoritminin həddindən artıq yavaş işləməsinin və mərkəzi prosessoru (CPU) saatlarla 100% yükdə saxlamasının qarşısını almaq. `gzip` təxminən 5 GB-lıq xam bazanı 3 GB civarına endirərək həm sürətli paketləmə, həm də optimal fayl ölçüsü təmin edir.

### 🚀 Gələcək Planlar (KhazarOS 2.0 Yol Xəritəsi)
- [ ] Xüsusi KhazarOS Proqram Repozitoriyasının (Repo Serverinin) qurulması.
- [ ] Azərbaycanın milli rəqəmsal imza (e-imza) və ASAN İmza sistemlərinin birbaşa inteqrasiyası.
- [ ] Kibertəhlükəsizlik tədqiqatçıları üçün məşhur OSINT və şəbəkə analiz alətlərinin hazır quraşdırılmış şəkildə gəlməsi.

[Back to Top ↑](#-khazaros-gnulinux-10-khazar)

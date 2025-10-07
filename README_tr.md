## Language Selection:

[**English**](README.md) | [**فارسی**](README_fa.md) | [**中文**](README_zh.md) | [**Русский**](README_ru.md) | [**Türkçe**](README_tr.md) | [**العربية**](README_ar.md)

![PeDitX Banner](https://raw.githubusercontent.com/peditx/luci-theme-peditx/refs/heads/main/luasrc/brand.png)  

---

# OpenWrt için DNS Jumper

Bu, OpenWrt üzerindeki LuCI paneli için basit ve verimli bir araçtır. Yönlendiricinizin DNS sunucularını kolayca ve hızlıca yönetmenizi ve değiştirmenizi sağlar.



## 🚀 Özellikler

* **Hızlı DNS Değiştirme:** Tek bir tıklama ile yönlendiricinizin DNS'ini popüler sunucular (Shecan, Electro, Cloudflare, Google vb. gibi) veya kendi özel sunucularınız arasından değiştirin.
* **Hız Testi (Ping):** Ağınız için en iyi ve en hızlı seçeneği bulmak amacıyla her bir DNS sunucusunun yanıt süresini doğrudan yönlendiricinizden test edin.
* **Akıllı Sıralama:** DNS listesini en düşük ping'e (en hızlı sunucuya) göre otomatik olarak sıralayın.
* **Tam Liste Yönetimi:**
    * Kolayca yeni DNS sunucuları ekleyin.
    * İhtiyaç duymadığınız sunucuları silin.
    * Daha hızlı erişim için favori sunucularınızı bir yıldızla ⭐ işaretleyin.
    * Sürükle ve Bırak (Drag & Drop) ile görüntülenme sırasını manuel olarak değiştirin.
* **Yedekleme ve Geri Yükleme:** Özel DNS listenizin bir yedeğini oluşturun ve gerektiğinde geri yükleyin.
* **Çevrimiçi Güncelleme:** İnternetten en son listeyi alarak DNS sunucu listenizi güncelleyin.
* **Ağ Tanılama Aracı:** Seçtiğiniz DNS üzerinden özel alan adlarına veya IP'lere ping atmak için dahili bir araç.
* **Canlı İzleme:** Ağ trafiğini gerçek zamanlı olarak görüntüleyin (Passwall ile uyumlu).

## ⚙️ Kurulum

Bu aracı kurmanın iki yolu vardır:

### 1. Komut ile Doğrudan Kurulum (Önerilen)
Bir SSH istemcisi (PuTTY veya Terminal gibi) kullanarak yönlendiricinize bağlanın ve aşağıdaki komutu çalıştırın:

```sh
sh -c "$(curl -sL [https://peditx.ir/projects/DNSJumper/DNSumper](https://peditx.ir/projects/DNSJumper/DNSumper))"
```
Komut dosyası, tüm ön koşulları otomatik olarak yükleyecek ve gerekli dosyaları doğru konuma kopyalayacaktır.

### 2. PeDitXOS Mağazası Üzerinden
**PeDitXOS** işletim sistemini kullanıyorsanız, bu paketi doğrudan dahili mağazasından indirip kurabilirsiniz.

**Önemli Not:** Kurulum tamamlandıktan sonra, panelin doğru görüntülenmesi için tarayıcı sayfanızı (**Ctrl+Shift+R**) zorla yenileyin.

## 🖥️ Nasıl Kullanılır

1.  Kurulumdan sonra yönlendiricinizin LuCI yönetim paneline giriş yapın.
2.  Ana menüden **PeditXOS** bölümüne gidin ve ardından **DNS Jumper**'a tıklayın.
3.  Bu sayfada DNS listesini görüntüleyebilir, pinglerini test edebilir ve **Apply** düğmesine tıklayarak istediğiniz DNS sunucusunu etkinleştirebilirsiniz.

---

## Özel Teşekkürler

- [PeDitX](https://github.com/peditx)  
- [PeDitXRT](https://github.com/peditx/peditxrt)  
- [OpenWrt](https://github.com/openwrt)  
- [Bootstrap Theme](https://github.com/twbs/bootstrap)
- [Mohamadreza Broujerdi](https://t.me/MR13_B)
- [Sia7ash](https://github.com/Sia7ash)


---

© 2018–2025 PeDitX. All rights reserved.  
For support or inquiries, join us on [Telegram](https://t.me/peditx).

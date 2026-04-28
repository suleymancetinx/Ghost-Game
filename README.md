# 👻 Ghost Catcher: Wall Edition

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

## 🎮 Oyun Hakkında
**Ghost Catcher: Wall Edition**, oyuncuların hayaletlere yakalanmadan labirentten kaçmaya çalıştığı, tarayıcı tabanlı dinamik bir bulmaca/kaçış oyunudur. 

Oyun alanı her seviyede rastgele (procedural) olarak yeniden oluşturulur ve seviye ilerledikçe engellerin ve hayaletlerin sayısı artar. Hiçbir harici kütüphane veya oyun motoru kullanılmadan, tamamen **Vanilla JavaScript** ile geliştirilmiştir.

## ✨ Temel Özellikler
* **Dinamik Harita Üretimi:** Her oyunda duvarların ve çıkış kapısının yeri algoritmik olarak benzersiz şekilde oluşturulur.
* **Üç Farklı Zorluk Seviyesi:** * *Easy:* Daha az duvar, rastgele hareket eden tek hayalet.
  * *Medium:* Orta yoğunlukta labirent ve kısmen oyuncuyu takip edebilen yapay zekaya sahip hayaletler.
  * *Hard:* Yoğun duvarlar ve doğrudan oyuncuyu hedef alan akıllı (Smart AI) hayaletler.
* **Akıcı Animasyonlar:** CSS keyframes ile oluşturulmuş partikül arka planı, neon parlama efektleri ve çarpışma anındaki ekran sarsıntısı (shake) efekti.
* **Responsive Tasarım:** Hem bilgisayar klavyesi (Yön tuşları / WASD) hem de mobil/tablet cihazlar için ekrandaki dokunmatik yön butonları ile oynanabilirlik.

## 🕹️ Nasıl Oynanır?
1. Menüden zorluk derecesini seçip **Start Game** butonuna basın.
2. Mavi neon renkli oyuncuyu (**👤**) kontrol ederek yeşil renkli çıkış kapısına (**🚪**) ulaşmaya çalışın.
3. Çapraz hareket edilemez; sadece Yukarı, Aşağı, Sağa ve Sola gidilebilir. (Burası biraz sürpriz olsun)
4. Kırmızı neon renkli hayaletlere (**👻**) dokunursanız oyun biter!

## 💻 Kurulum ve Çalıştırma
Bu oyun sunucu veya veritabanı gerektirmez. Kodu çalıştırmak için `Ghost_Game.html` dosyasını indirip modern bir web tarayıcısında (Chrome, Safari, Edge vb.) açmanız yeterlidir.

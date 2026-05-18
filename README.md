# DSPIC33EP_Bootloader_V1.1
PLAB DS V1.1 için kullanılan bootloader program projesi.
# PLAB DS - Çalıştırma Dosyası

Bu depo (repository), PLAB DS cihazının donanımı üzerinde güvenli ve doğru bir şekilde çalışabilmesi için gerekli olan kritik dosyayı/kodları içermektedir.

## Kullanım ve Lisans Kısıtlamaları (ÖNEMLİ)

**Bu proje açık kaynaklı bir yazılım DEĞİLDİR.** Bu depoda yer alan tüm kodlar, yapılandırma dosyaları ve dökümanlar üzerindeki tüm haklar saklıdır. Bu dosyayı indiren veya erişim sağlayan herkes aşağıdaki şartları kabul etmiş sayılır:

* **Değişiklik Yasağı:** Bu dosya üzerinde hiçbir şekilde değişiklik, ekleme veya tersine mühendislik (reverse engineering) çalışması yapılamaz.
* **Çoğaltma ve Dağıtım Yasağı:** Bu dosya veya içerdiği kod blokları, benzeri projelerde kullanılmak üzere kısmen veya tamamen kopyalanamaz, çoğaltılamaz ve başka platformlarda (GitHub forkları dahil) yeniden dağıtılamaz.
* **Kullanım Amacı:** Bu dosya yalnızca cihazın orijinal donanımı üzerinde, sağlandığı haliyle çalıştırılması amacıyla kullanılabilir. Ticari veya kişisel başka hiçbir projeye entegre edilemez.

## Kurulum ve Kullanım

1.	MPLAB X IDE içerisinde MCC eklentisi kullanılarak application kodunuz cihaz ile uyumlu bir şekilde çalıştırılır. 
2.	MCC içerisinde “16-bit Bootloader” kütüphanesini kurmanız gerekmektedir.
3.	MCC ile pin konfigürasyonlarını istediğiniz şekilde yapabilirsiniz.
4.	Device Resources kısmı içerisinde “16-bit Bootloader” seçeneği altında “16-bit Bootloader: Application” seçeneğine çift tıklayarak programınıza dahil etmelisiniz. 
5.	Daha sonra Bootloader projesini indirip “Browse” seçeneğine tıklayarak Bootloader’ı uygulamaya tanıtmış olursunuz. Bu sayede MPLAB projenizi yüklerken otomatik olarak Bootloader’ın yüklü olduğu adresi atlayarak Application için ayrılan kısma programınızı yazacaktır. 

## İletişim ve İzinler

Bu dosyanın yukarıda belirtilen amaçlar dışında kullanımı, lisanslanması veya ticari iş birlikleri için lütfen iletişime geçin:

* **E-posta:** suport.plab@gmail.com

---
Copyright © 2026 ATER DEKORASYON İNŞAAT MAKİNA ELEKTRİK ELEKTRONİK MOBİLYA SANAYİ TİCARET LİMİTED ŞİRKETİ. Tüm Hakları Saklıdır.

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/66/Openlogo-debianV2.svg" width="220">
  <h1 align="center">Debian Debloater</h1>
  <p align="center">[EN] Removes unnecessary packages on Debian.</p>
  <p align="center">[TR] Debian'daki gereksiz paketleri kaldırır.</p>
</div>


# [TR] BU ŞEY NEYE YARIYOR?

Debian'daki LibreOffice programları, yazıcı sürücüsü, Bluetooth sürücüsü, Wi-Fi sürücüsü ve daha birçok gereksiz paketleri kaldırır.

Bu işlemle birlikte sisteminiz büyük bir ölçüde hafifler ve daha performanslı çalışır.

# [TR] PEKİ NASIL KURULUYOR?

Debloat işleminin en kolay yöntemi kopyalayıp yapıştırma yöntemi.

Bunun için yukarıdaki .sh dosyaları arasından kullandığınız masaüstü ortamını seçin ve oradaki kodları terminale girin.

Eğer terminal ile kurmak istiyorsanız ilk önce aşağıdaki komutu girin.

```
git clone https://github.com/KaptanLingu/debian-debloater.git && cd debian-debloater && chmod +x *.sh
```

Son olarak kendi dağıtımınıza göre .sh komutunu girin. Mesela GNOME kullananlar `./gnome.sh`, LXDE kullananlar `./lxde.sh` komutunu kullanmalılar.

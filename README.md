# Raspberry-Pi
Raspberry Pi' yı açtığımız da otomatik olarak kablosuz ağa bağlanmasını sağlayabiliriz.
Linux aracılığı ile bu işlemi yapabilmemiz için 'boot/' dizinine giderek 'wpa_supplicant.conf' dosyası oluşturacağız.
Yapacağımız bu ayar ile Raspberry Pi'yımız için açılış esnasında kablosuz ağ bağlantı önceliği tanımlayacağız.
Sonuç olarak Raspberry Pi, ilk belirlediğimiz kablosuz ağ bağlantısı olumsuz olur ise ikinci belirlediğimiz kablosuz ağ için bağlantı sağlayacaktır.

# nucoos-deb-quickshell

Debian 13 (Trixie) için otomatik derlenen Quickshell `.deb` paketleri.

Quickshell, Qt6 ve QtQuick kullanarak durum çubukları, widget'lar, kilit
ekranları ve diğer masaüstü bileşenleri oluşturmaya yarayan esnek bir
araç setidir. Wayland ve X11 destekler.

## Kurulum

Releases bölümünden en güncel `.deb` dosyasını indirip:

    sudo apt install ./quickshell_0.2.1_amd64.deb

## Derleme

Paket, GitHub Actions üzerinde Debian Trixie konteynerinde otomatik derlenir.
Elle tetiklemek için Actions sekmesinden "Build Quickshell deb" workflow'unu
Run workflow ile başlatabilirsiniz.

## Lisans

Quickshell, GNU LGPL 3.0 altında lisanslanmıştır.
Kaynak: https://github.com/quickshell-mirror/quickshell
# Maintainer: Colin Keenan <colinnkeenan at gmail dot com>

pkgname=update
pkgver=1.1
pkgrel=1
pkgdesc="simple script and desktop file for doing a system update using yaourt"
arch=('any')
url="https://github.com/colinkeenan/update"
license=('GPL')
depends=('yaourt')
install=${pkgname}.install

source=('update' 'update.desktop')
md5sums=('99ed50e06a588985e98959ebcbb6bf4d'
         'b285ed4d13055f135a278c93208135bb')

package() {
  install -d -m755 "$pkgdir/usr/bin"
  install -d -m755 "$pkgdir/usr/share/applications"
  install -m755 update.desktop "$pkgdir/usr/share/applications"
  install -m755 update "$pkgdir/usr/bin"
}

# Maintainer: Colin Keenan <colinnkeenan at gmail dot com>

pkgname=update
pkgver=1.0
pkgrel=3
pkgdesc="GUI for 'mv': Adds 'Move or Rename' to 'open-with' context menu for most files."
arch=('any')
url="https://github.com/colinkeenan/update"
license=('GPL')
depends=('yad')       # had to use yad instead of zenity to have default values in forms
install=${pkgname}.install

source=('update' 'update.desktop')
md5sums=('0be87bf59a88a05c283ca252e3bcb020'
         'b285ed4d13055f135a278c93208135bb')

package() {
  install -d -m755 "$pkgdir/usr/bin"
  install -d -m755 "$pkgdir/usr/share/applications"
  install -m755 update.desktop "$pkgdir/usr/share/applications"
  install -m755 update "$pkgdir/usr/bin"
}

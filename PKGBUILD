# Maintainer: Fabien POLETTE <fabien.polette@protonmail.com>
pkgname=gnmic
pkgver=0.19.1
pkgrel=1
pkgdesc="A gNMI CLI client that provides full support for Capabilities, Get, Set and Subscribe RPCs with collector capabilities."
arch=('x86_64')
url="https://gnmic.kmrd.dev/"
license=('APACHE')
source=("https://github.com/karimra/$pkgname/releases/download/v$pkgver/${pkgname}_${pkgver}_Linux_${arch}.tar.gz")
sha256sums=('4b2440db04f52f56b451eaebb2a773b7f6275a36e6ac273b6c922d7c89ed47ae')

package() {
  # Install Binary
  install -Dm755 $srcdir/gnmic $pkgdir/usr/bin/gnmic
}

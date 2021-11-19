# Maintainer: Fabien POLETTE <fabien.polette@protonmail.com>
pkgname=gnmic
pkgver=0.20.4
pkgrel=1
pkgdesc="A gNMI CLI client that provides full support for Capabilities, Get, Set and Subscribe RPCs with collector capabilities."
arch=('x86_64')
url="https://gnmic.kmrd.dev/"
license=('APACHE')
source=("https://github.com/karimra/$pkgname/releases/download/v$pkgver/${pkgname}_${pkgver}_Linux_${arch}.tar.gz")
sha256sums=('746efabc9f98ec99ebaf15f7672dbc0bd4cc35e625a9b93d45b1341cac20fc73')

package() {
  # Install Binary
  install -Dm755 $srcdir/gnmic $pkgdir/usr/bin/gnmic
}

# Maintainer: @holmeslinux

pkgname=('jwm-wallpaper')
pkgver=16.06
pkgrel=1
pkgdesc='Wallpaper for Manjaro-JWM'
license=('CC-BY-SA 4.0')
arch=('any')
url="https://github.com/holmeslinux/$pkgname"
makedepends=('git')
source=("git+$url.git")
sha256sums=('SKIP')

package() {
  cd $srcdir/$pkgname
  install -Dm644 $pkgdir/usr/share/backgrounds/
}
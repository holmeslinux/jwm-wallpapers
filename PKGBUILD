# Maintainer: holmeslinux <holmes_holmes@live.com>

_snapshot=a18ceea78f8ce4e439db7ec68542c7232f271b1e
pkgname=jwm-wallpapers
pkgver=20160309
pkgrel=1
pkgdesc="Wallpapers for jwm"
arch=('any')
license=('GPL3')
url="https://github.com/holmeslinux/$pkgname"
source=("$pkgname-$pkgver-$pkgrel.tar.gz::$url/archive/$_snapshot.tar.gz")

md5sums=('baa70262cc8b397e9693f5a89b380475')

package() {
	cd $srcdir/$pkgname-$_snapshot
	install -dm755 $pkgdir/usr/share
	cp -r backgrounds $pkgdir/usr/share
+}
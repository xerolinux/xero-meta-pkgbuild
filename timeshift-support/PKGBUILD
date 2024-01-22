# Maintainer: DarkXero <info@techxero.com>

pkgname=timeshift-support
pkgver=0.2
pkgrel=2
pkgdesc='Support package for enabling Timeshift with timeshift-autosnap and grub-btrfs support'
arch=(any)
url='https://github.com/xerolinux/timeshift-support'
license=(GPL3)
depends=(timeshift timeshift-autosnap grub-btrfs)
makedepends=(git)
conflicts=(snapper-support snapper snap-pac)
source=(git+$url.git)
sha256sums=('SKIP')
install=$pkgname.install

package() {
    cp -a ${srcdir}/${pkgname}/usr ${pkgdir}
    rm "${srcdir}/${pkgname}/push.sh"
	rm "${srcdir}/${pkgname}/README.md"
	rm "${srcdir}/${pkgname}/LICENSE"
	rm "${srcdir}/${pkgname}/PKGBUILD"
}

# Maintainer: Your Name <youremail@domain.com>
pkgname=cgproxy-openrc
pkgver=VERSION
pkgver=20211030
pkgrel=1
pkgdesc="OpenRC cgproxy init script"
arch=('any')
license=('GPL')
groups=('openrc-world')
depends=('openrc' 'cgproxy')
provides=('init-cgproxy')
conflicts=('init-cgproxy')
source=("cgproxyd.initd")
sha256sums=('SKIP')

package() {
    install -Dm755 "${srcdir}"/cgproxyd.initd "${pkgdir}"/etc/init.d/cgproxyd
}

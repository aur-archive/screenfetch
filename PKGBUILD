# Maintainer: kittykatt <kittykatt@kittykatt.tk>
pkgname=screenfetch
pkgver=2.7.5
pkgrel=2
pkgdesc="Bash screenshot info grabber (DE, WM, theme, uptime, ...)"
arch=(any)
url="http://git.silverirc.com/cgit.cgi/screenfetch.git/"
license=('GPL')
conflicts=('screenfetch-git')
depends=('bash' 'xorg-xdpyinfo')
optdepends=('scrot: To take screenshot')
source=(http://git.silverirc.com/cgit.cgi/screenfetch.git/snapshot/${pkgname}-${pkgver}.tar.bz2)
md5sums=('822af684e02411b973f41e9e98469537')

build() {
	cd "$srcdir/${pkgname}-${pkgver}"

	install -d ${pkgdir}/usr/bin

	cp screenfetch-dev ${pkgdir}/usr/bin/screenfetch
}

# Maintainer: Nic0 <nicolas.caen@gmail.com>
# Contributor: Nic0 <nicolas.caen@gmail.com>

pkgname=pygtkpaste
pkgver=0.1
pkgrel=1
pkgdesc="A python front end for pastebin.com use"
url="http://www.nicosphere.net/pygtkpaste-une-application-gui-pour-pastebin-com-1836/"
arch=('i686' 'x86_64')
license=('GPL')
depends=('python' 'pygtk')
source=(http://src.nicosphere.net/$pkgname/$pkgname-$pkgver.py)
md5sums=('686f06fa67b723792ce95e3700402fc6')

build() {
    cd ${srcdir}
    install -d ${pkgdir}/usr/bin
    cp ${pkgname}-${pkgver}.py ${pkgdir}/usr/bin/${pkgname}
    chmod +x ${pkgdir}/usr/bin/${pkgname}
}

# Maintainer: Jonatan Bravo <zephrax@gmail.com>
pkgname=cap2hccap
pkgver=r22
pkgrel=1
pkgdesc="Convert pcap file to hashcat cap ones."
arch=('i686' 'x86_64')
url="http://sourceforge.net/projects/cap2hccap/"
license=('unknown')
depends=()
makedepends=()
optdepends=()
install=
changelog=
source=('http://downloads.sourceforge.net/project/cap2hccap/cap2hccap.tar.gz?r=http%3A%2F%2Fsourceforge.net%2Fprojects%2Fcap2hccap%2Ffiles%2F&ts=1341181808&use_mirror=ufpr')
md5sums=('14b71de122a9c3e0828448c5a207c409')

build() {
  cd ${srcdir}
  make
}

package() {
  cd ${srcdir}

  install -D cap2hccap.bin ${pkgdir}/usr/bin/cap2hccap
}

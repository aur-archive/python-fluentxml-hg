# Contributor: Vincent Berset <msieurhappy@gmail.com>

pkgname=python-fluentxml-hg
pkgver=95
pkgrel=1
pkgdesc="XML library written in python"
arch=('any')
url="http://fluentxml.last-exile.org/"
license=('GPL3')
depends=('python')
makedepends=('python' 'mercurial')
provides=(python-fluentxml)
conflicts=(python-fluentxml)
source=()
md5sums=()

_hgroot='http://hg.last-exile.org'
_hgrepo='FluentXML'

build() {
  cd $srcdir/$_hgrepo
  python ./setup.py install --root=$pkgdir
}

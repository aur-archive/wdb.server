# Automatically generated by pip2arch on 2015-03-02
# and extended by Serge Victor <arch@random.re>

pkgname=wdb.server
pkgver=2.0.7
pkgrel=1
pkgdesc="An improbable web debugger through WebSockets (server)"
url="http://github.com/Kozea/wdb"
depends=('python' 'python-tornado' 'tornado_systemd' 'python-psutil')
makedepends=('python3' )
license=('GPLv3')
arch=('any')
source=('https://pypi.python.org/packages/source/w/wdb.server/wdb.server-2.0.7.tar.gz')
md5sums=('223f444be7747e9392532c4ceeb658f2')

build() {
    cd $srcdir/wdb.server-2.0.7
    python setup.py build
}

package() {
    cd $srcdir/wdb.server-2.0.7
    python setup.py install --root="$pkgdir" --optimize=1 
}

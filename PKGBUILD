pkgname=python-markdown-math
pkgver=0.8
pkgrel=1
pkgdesc="Math extension for Python-Markdown"
arch=('x86_64')
url='http://pypi.python.org/pypi/python-markdown-math'
license=('BSD')
depends=('python3')
makedepends=('python3')
provides=('python3-markdown-math')
replaces=('python3-markdown-math')
conflicts=('python3-markdown-math')
source=("https://github.com/mitya57/${pkgname}/archive/refs/tags/${pkgver}.tar.gz")
sha256sums=('e700cbc53a857f443a782cc95f6a4d8ba4a264b12b67c3328b2f4f2f4156273f')

package() {
	cd "${pkgname}-${pkgver}"
	python3 setup.py install --root="$pkgdir" --optimize=0
}

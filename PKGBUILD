pkgname=python-markdown-math
pkgver=0.6
pkgrel=1
_index='78/e1/24021b30466ca2985352ec1f15b3cb38e0b62ba742c46820c33ddf7114a8'
pkgdesc="Math extension for Python-Markdown"
arch=('x86_64')
url='http://pypi.python.org/pypi/python-markdown-math'
license=('BSD')
depends=('python3')
makedepends=('python3')
provides=('python3-markdown-math')
replaces=('python3-markdown-math')
conflicts=('python3-markdown-math')
source=("https://files.pythonhosted.org/packages/${_index}/${pkgname}-${pkgver}.tar.gz")
sha256sums=('c68d8cb9695cb7b435484403dc18941d1bad0ff148e4166d9417046a0d5d3022')

package() {
  cd "${srcdir}/${pkgname}-${pkgver}"
  python3 setup.py install --root="$pkgdir" --optimize=0
}

pkgname='python3-markdown-math'
_pkgbasename=python-markdown-math
pkgver=0.5
pkgrel=1
pkgdesc="Math extension for Python-Markdown"
arch=('x86_64')
url='http://pypi.python.org/pypi/python-markdown-math'
license=('BSD')
depends=('python3')
makedepends=('python3')
source=("https://pypi.python.org/packages/62/a0/721bb6542cf4b48d6016a79786fb6d68b7a1368ec89ee6e30377d578457d/$_pkgbasename-$pkgver.tar.gz")
sha256sums=('8f8803c92ac0847d18bd82a51fdb6acec90b2b54a4990650e627a0d4d3a78445')

package() {
  cd "$srcdir/$_pkgbasename-$pkgver"
  python3 setup.py install --root="$pkgdir" --optimize=0
}

# Maintainer: Piotr Miller <nwg.piotr@gmail.com>
pkgname=('nwg-wrapper')
<<<<<<< HEAD
pkgver=0.1.2
=======
pkgver=0.0.2
>>>>>>> 82e55c3 (chore: bump to 0.0.2)
pkgrel=1
pkgdesc="Wrapper to display a script output or a text file content on the desktop in sway or other wlroots-based compositors"
arch=('any')
url="https://github.com/nwg-piotr/nwg-wrapper"
license=('MIT')
depends=('python' 'python-gobject' 'python-i3ipc' 'gtk3' 'gtk-layer-shell')
makedepends=('python-setuptools' 'python-wheel')
optdepends=('wlr-randr: for non-sway Wayland WMs support')
source=("$pkgname-$pkgver.tar.gz::https://github.com/nwg-piotr/"$pkgname"/archive/v"$pkgver".tar.gz")

<<<<<<< HEAD
md5sums=('a2211523b90feefaa3fe6599cb495549')
=======
md5sums=('c49160f31d4e12281a4c10b77bdb6679')
>>>>>>> 82e55c3 (chore: bump to 0.0.2)

package() {
  cd "${pkgname}-${pkgver}"
  python setup.py install --root="${pkgdir}" --optimize=1
}

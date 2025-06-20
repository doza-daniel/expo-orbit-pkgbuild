pkgname=expo-orbit
pkgver=2.1.0
pkgrel=1
pkgdesc="Accelerate your development workflow with one-click build launches and simulator management"
arch=('x86_64')

depends=()
optdepends=()

source=("https://github.com/expo/orbit/releases/download/expo-orbit-v$pkgver/expo-orbit-$pkgver-$pkgrel.$arch.rpm")

sha256sums=('36904f6998fce62f929f30607622d5d0dc24bff1251d20f5c2e206b9caf49d24')

package() {
    find $srcdir/ -mindepth 1 -maxdepth 1 -type d | xargs cp -r -t "$pkgdir"
}

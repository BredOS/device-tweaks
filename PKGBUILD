# Maintainer: Panda <panda@bredos.org

pkgname=bakery-device-tweaks
pkgver=$(date -u +%Y%m%d)
pkgrel=1
pkgdesc="Device-specific tweaks for BredOS"
arch=('any')
url="https://github.com/BredOS/device-tweaks"
license=('GPL')
source=("tweaks.yaml")
md5sums=('4ce679deb1e83336b78de7c49f797cdd')

package() {
    install -Dm644 "${srcdir}/tweaks.yaml" "${pkgdir}/usr/share/bakery/tweaks.yaml"
}


# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-kitty-config
pkgver=1
pkgrel=1
pkgdesc="Kitty config for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('GPL3')
depends=('kitty')
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -d "${pkgdir}/etc/skel/.config/kitty/"
    install -Dm 644 "kitty.conf" "${pkgdir}/etc/skel/.config/dunst/kitty.conf"
}


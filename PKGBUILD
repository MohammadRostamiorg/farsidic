pkgname=farsidic
pkgver=1.0
pkgdesc="A simple package that helps you to set your linux system DNS servers to several DNS servers"
url="https://github.com/mohammadrostamiorg/dnsChanger"
arch=('any')
license=('MIT')
maintainer="Mohammad Rosstami <mohammad.jayant@gmail.com>"
source=("script.sh" "index.json")
depends=('bash' 'coreutils' 'jq')
pkgrel=1
sha256sums=("SKIP" "SKIP")
package() {
  install -Dm755 script.sh "${pkgdir}/usr/bin/farsidic"
  install -Dm644 index.json "${pkgdir}/etc/farsidic/index.json"
}

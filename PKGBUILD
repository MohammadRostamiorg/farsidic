pkgname=farsidic
pkgver=1.1
pkgdesc="A simple farsi dictionary"
url="https://github.com/mohammadrostamiorg/farsidic"
arch=('any')
license=('GPL-3')
maintainer="Mohammad Rosstami <mohammad.jayant@gmail.com>"
source=("script.sh" "https://raw.githubusercontent.com/MohammadRostamiorg/farsidic/refs/heads/master/dictionaries.tar.gz")
depends=('bash' 'coreutils' 'jq')
pkgrel=1
sha256sums=("SKIP" "SKIP")
package() {
  install -Dm755 script.sh "${pkgdir}/usr/bin/farsidic"
  install -Dm644 dictionaries.tar.gz "${pkgdir}/etc/farsidic/dictionaries.tar.gz"
  tar -xzf dictionaries.tar.gz -C "${pkgdir}/etc/farsidic/"
}

# Maintainer: Jeremy Pope <jpope@jpope.org> PGP-Key: E00B4261
pkgname=cui-git
pkgver=0.1.2
pkgrel=1
pkgdesc="CUI is a cower wrapper with KDE bindings."
url='https://jpope.org'
license=('wtfpl')
arch=('i686' 'x86_64')
depends=('kdebase-kdialog' 'kdebase-dolphin' 'kdebase-katepart')
makedepends=()
optdepends=()
provides=('cui')
conflicts=('cui')
source=('cui'
        'cui.desktop')
package() {
  install -Dm755 cui $pkgdir/usr/bin/cui
  install -Dm644 cui.desktop $pkgdir/usr/share/applications/cui.desktop
}
sha256sums=('8017cb3a194e4d9d7868833379b169afbf70a6e243b68a2bace99aa5ffeb47e6'
            'a980a4d5697fc684f49ae7b41f7036fab645e74a1237754b199cf810a939be77')

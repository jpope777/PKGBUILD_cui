# Maintainer: Jeremy Pope <jpope@jpope.org> PGP-Key: E00B4261
pkgname=cui-git
pkgver=0.1
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
sha256sums=('5bdb84a55312ef813a68fe83b267b5068d8fcbaec56e69d51a79864d031c7d50'
            'a980a4d5697fc684f49ae7b41f7036fab645e74a1237754b199cf810a939be77')
package() {
  install -Dm755 cui $pkgdir/usr/bin/cui
  install -Dm644 cui.desktop $pkgdir/usr/share/applications/cui.desktop
}

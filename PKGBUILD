# Maintainer: Jeremy Pope <jpope@jpope.org> PGP-Key: E00B4261
pkgname=cui-git
pkgver=0.1.3
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
sha256sums=('f9751966c3304a1e4d7d7f7e2c5b9784a62db2acb1fafe941abfea583b8a0d98'
            'a980a4d5697fc684f49ae7b41f7036fab645e74a1237754b199cf810a939be77')

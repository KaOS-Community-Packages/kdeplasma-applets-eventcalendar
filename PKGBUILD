pkgname=kdeplasma-applets-eventcalendar
_pkgname=plasma-applet-eventcalendar
pkgver=63
pkgrel=1
pkgdesc="Plasmoid for a calendar+agenda with weather that syncs to Google Calendar."
arch=(x86_64)
url="https://github.com/Zren/plasma-applet-eventcalendar"
license=()
depends=(kdeclarative)
source=("https://github.com/Zren/${_pkgname}/archive/v${pkgver}.tar.gz")
md5sums=('3fb7f76a32049c834d46cac1063e1873')

package() {
  install -dm755 "${pkgdir}/usr/share/plasma/plasmoids/"
  cp --preserve=mode -r "${_pkgname}-${pkgver}/package" "${pkgdir}/usr/share/plasma/plasmoids/org.kde.plasma.eventcalendar"
}

pkgname=kdeplasma-applets-eventcalendar
_pkgname=plasma-applet-eventcalendar
pkgver=76
pkgrel=1
pkgdesc="Plasmoid for a calendar+agenda with weather that syncs to Google Calendar."
arch=(x86_64)
url="https://github.com/Zren/plasma-applet-eventcalendar"
license=('GPL2')
depends=(kdeclarative)
source=("https://github.com/Zren/${_pkgname}/archive/v${pkgver}.tar.gz")
md5sums=('36b2018ad92df8d9e380096f804b9981')

package() {
  install -dm755 "${pkgdir}/usr/share/plasma/plasmoids/"
  cp --preserve=mode -r "${_pkgname}-${pkgver}/package" "${pkgdir}/usr/share/plasma/plasmoids/org.kde.plasma.eventcalendar"
}

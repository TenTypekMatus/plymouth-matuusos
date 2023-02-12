# Maintainer: Matus Mastena <Shadiness9530@proton.me>
pkgname=plymouth-theme-matuusos
pkgver=9999
pkgrel=1
pkgdesc='Plymouth theme for MatuusOS'
arch=($(arch))
depends=('plymouth')
focal_depends=()
makedepends=()
makedepends_x86_64=()
checkdepends=()
optdepends=()
focal_optdepends_x86_64=()
provides=()
conflicts=()
replaces=()
preinst=''
postinst=''
prerm=''
postrm=''
backup=()
options=()
license=()
url='https://github.com/MatuushOS'
source=('git+https://github.com/TenTypekMatus/plymouth-matuusos')
sha256sums=('SKIP')
package() {
    mkdir -p            ${pkgdir}/usr/share/plymouth/themes
    cp -r ${srcdir}     ${pkgdir}/usr/share/plymouth/themes
    plymouth-set-default-theme -R matuusos 
}

# vim: set sw=4 expandtab:

# Maintainer: 3V0LU710N <db_eee at yahoo dot com>

pkgname=gnomish-dark-theme-36
pkgver=20130711
pkgrel=1
pkgdesc="This is a clean dark theme for GTK3 / GTK2, based on Adwaita (provided by gnome-themes-standard), plus a matching GNOME-Shell theme. For GTK < 3.8 / Cinnamon."
arch=('any')
url="http://tsujan.deviantart.com/art/GnomishDark-300548460"
license=('CC')
source=('http://fc00.deviantart.net/fs70/f/2013/023/1/b/gnomishdark_by_tsujan-d4yxsoc.7z')
md5sums=('5d7008358097458a60ef099cdae3d0dd')
depends=('gtk-engine-murrine')
makedepends=('p7zip')
optdepends=('gnome-themes-standard: Default themes for the GNOME desktop' 'gnome-tweak-tool: A tool to customize advanced GNOME 3 options' 'gnome-shell-extension-user-theme: User Theme extension for GNOME Shell' 'nouvegnomegray-icon-theme: nouveGnomeGray is a gray icon set made for dark GTK themes')

build() {
  echo "Creating Package"
}

package() {
  cd "$srcdir"
  mkdir -p "${pkgdir}"/usr/share/themes
  cp -rf GnomishDark "${pkgdir}"/usr/share/themes/
  chmod 755 -R "$pkgdir/usr/share/themes"
}

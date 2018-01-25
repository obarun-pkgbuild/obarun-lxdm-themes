# Maintainer Eric Vidal <eric@obarun.org>

pkgname=obarun-lxdm-themes
pkgver=0.2
pkgrel=1
pkgdesc='Gtk3 lxdm themes for Obarun'
url='https://github.com/Obarun/obarun-lxdm-themes.git'
arch=(x86_64)
license=('ISC')
depends=('lxdm-gtk3')
backup=('etc/obarun/pacopts.conf')
makedepends=('git')
intall=obarun-lxdm-themes.install
sha1sums=('SKIP')
source=("${pkgname}::git+${url}#tag=v${pkgver}")
validpgpkeys=('6DD4217456569BA711566AC7F06E8FDE7B45DAAC') # Eric Vidal

package() {

  cd "$pkgname"
		 
  make DESTDIR="$pkgdir" install
}

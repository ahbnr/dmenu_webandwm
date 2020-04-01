pkgname=dmenu_webandwm
pkgver=1.0.0
pkgrel=1
pkgdesc="Use dmenu to launch programs, switch windows and search the web."
arch=('x86_64')
depends=('xdg-utils' 'awk' 'wmctrl' 'dmenu' 'zsh')

prepare() {
  cp -R $startdir/dmenu_webandwm $srcdir || true
  chmod +x $srcdir/dmenu_webandwm
}

build() {
  # nothing to do here
}

package() {
  mkdir -p "$pkgdir/usr/bin"
  cp dmenu_webandwm "$pkgdir/usr/bin"
}

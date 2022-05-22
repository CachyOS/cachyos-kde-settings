# Maintainer: Vladislav Nepogodin <nepogodin.vlad@gmail.com>

pkgname=cachyos-kde-settings
pkgdesc='CachyOS KDE settings'
pkgver=1.0.6
pkgrel=1
arch=('any')
url="https://github.com/cachyos/$pkgname"
license=('GPL')
makedepends=('coreutils')
source=("$pkgname-$pkgver.tar.gz::$url/archive/$pkgver.tar.gz")
sha512sums=('6d2a0916e5a94f3233f69b8380db4efbbda42f5889e6ca5a7cf0452da6fd49e2d96ecc46ebecb29db5452894a981e616826ce6c415212e2ba8fec4d00a8feda8')
depends=('cachyos-zsh-config'
         'lightly-git'
         'kvantum-qt5'
         'qt5ct'
         'nerd-fonts-fantasque-sans-mono'
         'noto-fonts'
         'ttf-fira-sans'
         'plasma5-applets-eventcalendar'
         'plasma5-applets-netspeed'
         'plasma5-applets-window-appmenu'
         'plasma5-applets-window-buttons'
         'plasma5-applets-window-title'
         'kwin-scripts-forceblur'
         'ksysguard'
         'char-white'
         'capitaine-cursors'
         'cachyos-nord-kde-theme-git'
         'cachyos-wallpapers'
         'cachyos-nord-gtk-theme-git')
install=$pkgname.install
provides=('cachyos-desktop-settings')
conflicts=('cachyos-desktop-settings')

package() {
    install -d $pkgdir/etc
    cp -rf $srcdir/$pkgname-$pkgver/etc $pkgdir
}

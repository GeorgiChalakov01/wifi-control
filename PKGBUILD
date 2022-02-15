# Maintainer: Your Georgi georgichalukov.main@gmail.com
pkgname='wifi-control'
pkgver=1
pkgrel=1
pkgdesc="Simple wifi control from dmenu."
arch=('x86_64')
url="https://github.com/GeorgiChalakov01/wifi-control.git"
license=('GPL')
depends=('dmenu' 'networkmanager' 'sed')
makedepends=('git')
source=('wifi-control::https://github.com/GeorgiChalakov01/wifi-control.git')
noextract=()
md5sums=('SKIP')

package() {
	sudo install -Dm755 ./wifi-control "/usr/bin/wifi-control"
}

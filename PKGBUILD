# Maintainer: BlackIkeEagle <ike DOT devolder AT gmail DOT com>

pkgname=jsonlint
_npmname=jsonlint
pkgver=1.6.0
pkgrel=2
pkgdesc="Validate JSON"
arch=('any')
makedepends=('npm')
depends=('nodejs')
url="http://zaach.github.io/jsonlint/"
license=('MIT')
provides=('nodejs-jsonlint')

package() {
	local _npmdir="$pkgdir/usr/lib/node_modules/"
	mkdir -p $_npmdir
	cd $_npmdir
	npm install --user root -g --prefix "$pkgdir/usr" $_npmname@$pkgver
}

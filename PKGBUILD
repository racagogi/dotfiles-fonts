pkgname=raca-fonts
pkgver=20250213
pkgrel=1
pkgdesc="collections of fonts for cjk users"
license=("OFL-1.1")
arch=(any)
provides=(ttf-font ttf-freefont ttf-fonts adobe-source-code-pro-fonts cantarell-fonts)
source=(raca-fonts.tar)
sha256sums=('SKIP')

package() {
	install -Dt $pkgdir/usr/share/fonts/$pkgname/gothicA1 -m644 gothica1/*
	install -Dt $pkgdir/usr/share/fonts/$pkgname/gowunBatang -m644 gowunbatang/*
	install -Dt $pkgdir/usr/share/fonts/$pkgname/stix -m644 stix/*
	install -Dt $pkgdir/usr/share/fonts/$pkgname/symbols -m644 symbols/*
	install -Dt $pkgdir/usr/share/fonts/$pkgname/monaspace -m644 monaspace/*
	install -Dt $pkgdir/usr/share/fonts/$pkgname/noto-fonts -m644 noto-sans/*
}

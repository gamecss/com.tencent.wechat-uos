# Maintainer: DuckSoft <realducksoft@gmail.com>
pkgname=wechat-uos
pkgver=2.0.0
pkgrel=7
pkgdesc="UOS专业版微信 (迫真魔改版)"
arch=('x86_64')
depends=(gtk2 gtk3 libxss gconf nss lsb-release bubblewrap)
license=('custom')
source=('https://cdn-package-store6.deepin.com/appstore/pool/appstore/c/com.qq.weixin/com.qq.weixin_2.0.0_amd64.deb' 'uos-lsb' 'uos-release' 'wechat-uos' 'wechat-uos.desktop')
b2sums=('6abb4054ac7efc10bd093de8064a8972ef703d29f7fe2caf94a5be19230f861e77c1965ca78687aeea32016e6ab41d6d18d0610a9f11c351f92c114b06795972'
        '3cd62350b8b12d857e7a6b7d14ddc0fde9617f1e927371962f95ce633f7686c12ff3d8bc0e4048c85ef5a7414885ed03aecd8f7fbb6ca6f5e6d52d68273d4c43'
        '49de7f51a7d43acbdb5d6e54aa77e56476d79ff3bb950a99bfe6023c4eb067737fcfcdf51ea7d2428e7923659267bce8477bde71df00c4def1f8e16999d84a49'
        '2a05653c543b5843cef154938c491728aa8acade2024f4c1701ad5ae3c504540fc3a09fdc547689b176d231f80442bc154d289d2a74a20c62a0782babfd805ad'
        '13f84de388ff2c20f9e7c42b773e8dbd63da473851690ce37cb80966e2fac0843933d0d561c7c5f8918e456f56db9a66b82cbd5952b056a954b519ef76826ed2')
package() {
    tar xpf data.tar.xz -C "$pkgdir"
    install -Dm644 -t "$pkgdir"/opt/apps/com.qq.weixin/craps/ uos-lsb uos-release
    install -Dm755 wechat-uos -t "$pkgdir"/usr/bin/
    install -Dm755 wechat-uos.desktop -t "$pkgdir"/usr/share/applications/
    mkdir -p "$pkgdir"/usr/share/icons
    cp --no-preserve=o -at "$pkgdir"/usr/share/icons opt/apps/com.qq.weixin/entries/icons/hicolor
}

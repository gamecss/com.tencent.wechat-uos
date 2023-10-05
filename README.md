# Flatpak wrapper of wechat-uos

forked from [Archlinux user repository](https://aur.archlinux.org/cgit/aur.git/?h=wechat-uos) and [com.qq.QQ metadata](https://github.com/flathub/com.qq.QQ)

## Install
```sh
flatpak install org.freedesktop.Sdk org.electronjs.Electron2.BaseApp # Select 23.08 one
flatpak-builder --install build-dir com.tencent.wechat-uos.yaml # Install
```
Run by `flatpak run com.tencent.wechat-uos` or desktop icon.

=============
```markdown
# Maintainer: DuckSoft <realducksoft at gmail dot com>
# Maintainer: sukanka <su975853527 at gmail dot com>
# Contributor: sihuan <sihuan at sakuya.love>
# Contributor: Nick Cao <nickcao at nichi dot co>
# Contributor: Xuanwo <xuanwo@archlinuxcn.org>
```
```yaml
source = license.tar.gz
sha512sums = 8b9d70162a5a71584cf85a309da48730de9db03f49a7e9611de04441864be80267e53e3155f7856c87ed53f99def277d74132392816c4f07893a02e99043ed6c
source_x86_64 = wechat-2.1.5-x86_64.deb::https://home-store-packages.uniontech.com/appstore/pool/appstore/c/com.tencent.weixin/com.tencent.weixin_2.1.5_amd64.deb
sha512sums_x86_64 = 89bc2c8c087b744e245f39fee7d73f953c1349a68c493df1e4f0d187f2e7450d47ad7507fa6abcb91625c6240707da83f421f513d696eb5fc95b808ef779fc95
source_aarch64 = wechat-2.1.5-aarch64.deb::https://home-store-packages.uniontech.com/appstore/pool/appstore/c/com.tencent.weixin/com.tencent.weixin_2.1.5_arm64.deb
sha512sums_aarch64 = 905750c7c23aa17e8c04a2cd5f91f055f9a88794b9945437afc1c8b43c0443745da32094c7523ecbfa2d61c5699fa465062d56b241e49f5d3b09faa2ba36bd8e
```

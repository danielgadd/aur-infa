# Maintainer: Daniel Gadd <hello@gadd.co.nz

pkgname=infra
pkgdesc='Instantly manage and monitor Kubernetes from your Desktop.'
licence='custom: commercial'
pkgver=0.33
pkgrel=1
arch=('x86_64')
url='https://infra.app'
source=("https://download.infra.app/linux/${pkgname/_/}_latest_amd64.deb")
sha256sums=('48b32b5688f646ac5365112a761d6dbbfd8b7cf878aa1d36f181e09783148c7d')

package() {
  tar -xf data.tar.xz -C "${pkgdir}"
}

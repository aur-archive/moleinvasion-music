# Maintainer: archtux <antonio dot arias99999 at gmail dot com>

pkgname=moleinvasion-music
pkgver=0.4
pkgrel=3
pkgdesc="Music for moleinvasion."
arch=('any')
url="http://moleinvasion.tuxfamily.org"
license=('Licence Art Libre')
source=('ftp://download.tuxfamily.org/minvasion/music/02-La_nuit_de_Monsieur_Personne.ogg' \
        'ftp://download.tuxfamily.org/minvasion/music/04-A_travers_la_fenetre.ogg' \
        'ftp://download.tuxfamily.org/minvasion/music/05-Jecoute_mais_je_ne_vois_rien.ogg' \
        'ftp://download.tuxfamily.org/minvasion/music/07-La_lune_eclaire_mes_pas.ogg' \
        'ftp://download.tuxfamily.org/minvasion/music/08-Night_of_love.ogg' \
        'ftp://download.tuxfamily.org/minvasion/music/09-Paradoxe.ogg' \
        'ftp://download.tuxfamily.org/minvasion/music/09-Partir.ogg' \
        'ftp://download.tuxfamily.org/minvasion/music/Always%20120bpm.ogg' \
        'ftp://download.tuxfamily.org/minvasion/music/celtic%20escape.ogg' \
        'ftp://download.tuxfamily.org/minvasion/music/concerto-test.ogg' \
        'ftp://download.tuxfamily.org/minvasion/music/concerto.ogg' \
	'ftp://download.tuxfamily.org/minvasion/music/longtail.ogg' \
	'ftp://download.tuxfamily.org/minvasion/music/mole-invasion-ghost01.ogg' \
	'ftp://download.tuxfamily.org/minvasion/music/mole-invasion-jazzy01.ogg' \
	'ftp://download.tuxfamily.org/minvasion/music/mole-invasion-jazzy02.ogg' \
	'ftp://download.tuxfamily.org/minvasion/music/mole-invasion-jungle01.ogg' \
	'ftp://download.tuxfamily.org/minvasion/music/mole-invasion-softy01.ogg' \
	'ftp://download.tuxfamily.org/minvasion/music/mole-invasion-softy02.ogg' \
	'ftp://download.tuxfamily.org/minvasion/music/mole-invasion-softy03.ogg' \
	'ftp://download.tuxfamily.org/minvasion/music/mole-invasion-tension01.ogg' \
	'ftp://download.tuxfamily.org/minvasion/music/mole-invasion-timed01.ogg' \
	'ftp://download.tuxfamily.org/minvasion/music/piano%20kill.ogg' \
	'ftp://download.tuxfamily.org/minvasion/music/symphonie%20nocturne.ogg' \
	'ftp://download.tuxfamily.org/minvasion/music/tentatives%20orchestrale.ogg')
md5sums=('e5f67a3a150400d81b6c2d0ef79cbf91' '2ca7c430e938981af30d4a00b8dbe4ed' '7f42f77966cb88b8aef07f2d5cfa6098' \  
	 '2e775c4d5e57e11cf06dac8b7c3dd41d' '1c30a51a9b14dea87db307f6ead7d2ce' 'de367a6119cfc22aabb43b927037d909' \  
	 '23e577de78cf89a6b01886ea9964ed1d' '2fbd7421a5356355ae5fe4c60dcab371' '941daa3b956156cdf9a7ef985d01ed97' \
	 '600a450478e0f0b13bf60800f16ac82f' '694b7674777bd9d2aa402a5413ece524' 'ffabfca3c542c949fd5dc2f6122d0a93' \  
	 'ea63970bc0396b6b18261a9b258385f0' 'faa116b1bdf34d7a2e7ef78c6797c073' '0f9cf97205354be3fbf37a6aee1a6167' \ 
	 '42d619a2ef26b002f1b160097dce90c9' '3e0fec7fe67897674d959f863b9409f9' '80b4581ee06511fcaa4ffe3a34822d1e' \  
	 '7387f7d4eb7dd39b920f80142f045fb7' 'b782b246ee558a374a4e916e76d4900c' 'fcd1f5e78947fad90f704de2212678a0' \
	 '5a109296d3a1a28e98713be33c3a2f2b' 'b20e2fe873994002b65c9d5ddd0ad5cc' 'c54bbf5e034b6155bbcd9c4b1c2ad9f3')


package() {
	cd $startdir
        mv Always%20120bpm.ogg 'Always 20bpm.ogg'
        mv celtic%20escape.ogg 'celtic escape.ogg'
        mv piano%20kill.ogg 'piano kill.ogg'
        mv symphonie%20nocturne.ogg 'symphonie nocturne.ogg'
        mv tentatives%20orchestrale.ogg 'tentatives orchestrale.ogg'
	mkdir -p $pkgdir/usr/share/moleinvasion/music
        cp -R *.ogg $pkgdir/usr/share/moleinvasion/music
}
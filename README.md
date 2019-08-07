# ft_linux

## Prerequis du systeme hote
	- OK (voir version-check.sh)
	- Add controleur SATA 20G pour LFS
	- New partitions (voir fdisk + cfdisk)
		- Size, type(L)
		- Creation systeme de fichier sur partition
		- Monter partition avec point de montage

	- Telechargement paquets (374 Mo)


## Commandes utiles
	- blkid (UUIDs de chaque partion)
	- fdisk / cfdisk
	- mkfs -v -t ext4 /dev/<xxx>
	- mkswap /dev/<yyy>
	- mount

## Fichiers utiles
	- /etc/fstab
	- /etc/mtab

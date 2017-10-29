# Vagrant - Phabricator Ansible

Vagrant file Ansible Phabricator Deployment untuk tugas UTS OSS

Informasi mengenai [Phabricator], [Ansible], dan [Vagrant] beserta [VirtualBox].

## Requirements

Harus sudah terinstall `Vagrant` dan `VirtualBox`

Instalasi Vagrant ada di [sini](https://www.vagrantup.com/downloads.html)
Instalasi VirtualBox ada di [sini](https://www.virtualbox.org/wiki/Downloads)

## Panduan Instalasi

Clone repositori ini
```sh
git clone https://github.com/kuwali/uts-oss.git
cd uts-oss
```
Tambahkan box `ubuntu/xenial64`
```sh
vagrant box add ubuntu/xenial64
```
Lakukan `vagrant up`
```sh
vagrant up
```

## Penggunaan

Silahkan akses `192.168.100.21`

## Contribute

Silahkan lakukan Pull Request. Hubungi pengembang di kustiawanto.halim@gmail.com

## License
[LICENSE]

[Phabricator]: <https://www.phacility.com/phabricator/>
[Ansible]: <https://www.ansible.com/>
[Vagrant]: <https://www.vagrantup.com/>
[VirtiualBox]: <https://www.virtualbox.org/>
[LICENSE]: <https://github.com/kuwali/tugas-5-oss/blob/master/LICENCE>

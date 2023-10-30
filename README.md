Getting started
---------------

To get started building for Galaxy A10s (Codename: a10s), you'll need to get
familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html).

Init your AOSP manifest first, then clone our manifest to .repo/local_manifests:
```
git clone https://github.com/SuzuhimeDevelopment/manifests -b lineage-17.1 .repo/local_manifests
```
Then to sync up:
```
repo sync -j$(nproc --all) --force-sync --no-tags --no-clone-bundle
```

Credits:
========
 * [**ItzKaguya**](https://github.com/Hirozuto)
 * [**rsuntk**](https://github.com/rsuntk)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**Renelz**](https://github.com/renelzx)
 * [**Batuhantrkgl**](https://github.com/batuhantrkgl)
 * [**Lê Minh Trí**](https://github.com/crazyads69)
 * [**HotaruZera**](https://github.com/zhueszka)
 * [**Entire Devs and Testers on Galaxy A10s Development - Indonesia**](https://t.me/SamsungA10sID)

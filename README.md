# OpenWrt packages feed

## Description

This is the OpenWrt "packages"-feed containing community-maintained build scripts, options and patches for applications, modules and libraries used within OpenWrt.

Installation of pre-built packages is handled directly by the **opkg** utility within your running OpenWrt system or by using the [OpenWrt SDK](https://openwrt.org/docs/guide-developer/obtain.firmware.sdk) on a build system.

## Usage

This repository is intended to be layered on-top of an OpenWrt buildroot. If you do not have an OpenWrt buildroot installed, see the documentation at: [OpenWrt Buildroot – Installation](https://openwrt.org/docs/guide-developer/build-system/install-buildsystem) on the OpenWrt support site.

This feed is enabled by default. To install all its package definitions, run:
```
./scripts/feeds update packages
./scripts/feeds install -a -p packages
```

## License

See [LICENSE](LICENSE) file.
 
## Package Guidelines

See [CONTRIBUTING.md](CONTRIBUTING.md) file.

edit:

clone the reposotory with 
"git clone https://github.com/donkey42/packages.git"
then checkout the branch required
"git checkout <required branch>"

for attitude_adjustment "git checkout attitude_adjustment"
for barrier_breaker "git checkout barrier_breaker"
for chaos_calmer "git checkout chaos_calmer

or just do one git clone command
for attitude_adjustment "git clone -b for-12.09 https://github.com/donkey42/packages.git"
for barrier_breaker "git clone -b for-14. https://github.com/donkey42/packages.git"
for chaos_calmer "git clone -b chaos_calmer https://github.com/donkey42/packages.git"

donkey

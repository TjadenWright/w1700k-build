# w1700k-build

## Notes: 
`git submodule add https://github.com/OpenWRT-fanboy/OpenW1700k.git OpenW1700k`
`git submodule add https://github.com/rchen14b/luci-app-w1700k-fancontrol Apps/luci-app-w1700k-fancontrol`
`git submodule add https://github.com/rchen14b/luci-app-airoha-npu Apps/luci-app-airoha-npu`

`./custom-apps`
`cd OpenW1700k; make menuconfig; cd ..;`
`cd OpenW1700k; export PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/lib/wsl/lib; make -j$(nproc); cd ..;`
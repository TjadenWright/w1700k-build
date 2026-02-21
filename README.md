# w1700k-build

## Notes: 
### For Minimal:
`git submodule add https://github.com/OpenWRT-fanboy/OpenW1700k.git OpenW1700k`
`git submodule add https://github.com/rchen14b/luci-app-w1700k-fancontrol Apps/luci-app-w1700k-fancontrol`
`git submodule add https://github.com/rchen14b/luci-app-airoha-npu Apps/luci-app-airoha-npu`

### Optional: 
`git submodule add https://github.com/vad-b/luci-app-tailscale-ng Apps/luci-app-tailscale-ng`
`git submodule add https://github.com/animegasan/luci-app-wolplus Apps/luci-app-wolplus`
`git submodule add https://github.com/jerrykuku/luci-theme-argon Apps/luci-theme-argon`

## Configs
### Default Minimal Branch Config
`default.config`

### Custom Minimal Branch Config
`custom.config`

## Commands
`./custom-apps`
`./menu-config`
`./build-openwrt`
`./config-save <CONFIG_NAME>`
`./config-deploy <CONFIG_NAME>`
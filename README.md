# 小胖的XiaoMi Wifi MINI的定制固件

## 1、修改登录界面的 CSS 样式文件

编译前，可以在下面两个路径进行修改

```
./feeds/small8/luci-theme-argonne/htdocs/luci-static/argonne/css/cascade.css
./feeds/kenzo/luci-theme-argonne/htdocs/luci-static/argonne/css/cascade.css
```

编译好以后，在系统内，该设置文件的路径是
`/www/luci-static/argonne/css`

## 2、修改 argon 的默认配置文件

编译前，可以在下面两个路径进行修改
```
./feeds/small8/luci-app-argonne-config/root/etc/config/argonne
./feeds/kenzo/luci-app-argonne-config/root/etc/config/argonne
```

编译好以后，系统内的 argonne 设置文件的路径是
 `/etc/config/argonne` 
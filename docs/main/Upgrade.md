# 升级
1. 下载新版本对应你的系统的二进制版本zip文件，并解压；
2. 停止正在运行的TeaWeb服务，可以在原有目录下运行 `bin/teaweb stop`；
3. 将 **除configs/** 目录外的所有文件拷贝到原有目录下，并替换原有文件；
4. 使用命令 `bin/teaweb restart` 重启服务，升级完成。

## v0.0.9
从 v0.0.9以前的版本升级时，请把新的版本的 `configs/widgets` 目录拷贝到老版本的 `configs/` 目录下。